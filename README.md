# Bài tập môn học Lập trình Unity

Đường link Driver của file game (Đã nén RAR): 

https://drive.google.com/drive/u/1/folders/1Rqzux3UFzpc8RZrsvmv-HExIP8FsGusC



Các thành viên nhóm bao gồm:
1. Trưởng nhóm: Đặng Hoàng Nam (K1954 8010 6015)
2. Triệu Văn Đông (K1954 8010 6004)
3. Hoàng Thị Hường (K1954 8010 6013)
4. Phạm Như Thanh (K1954 8010 6021)



Phân công công việc nhóm:
- Thiết kế game và code: Đặng Hoàng Nam
- Thiết kế âm thanh và nhân vật: Triệu Văn Đông
- Viết báo cáo Word: Hoàng Thị Hường
- Viết báo cáo PowerPoint: Phạm Như Thanh



Logic chơi game:
- Khi chạy trò chơi sẽ hiện ra menu màn hình chính, có 3 tùy chọn: Chơi mới, Cài đặt, Thoát
- Bấm chơi mới sẽ chuyển cảnh sang màn chơi thứ 1, bấm nút Thoát sẽ thoát chương trình, nút Cài đặt chưa có công dụng
- Người chơi sử dụng A,W,S,D để di chuyển, nút Space hoặc chuột trái để tấn công
- Phía dưới thanh máu người chơi có một nút menu. Khi bấm vào sẽ mở ra menu thông tin nhân vật, loại vũ khí, trang phục người chơi, số vàng, số kinh nghiệm.
- Phía dưới vũ khí có một nút nâng cấp, hiển thị là số vàng dùng để nâng cấp. Vũ khí sẽ nâng cấp được tối đa 5 lần, mỗi lần sẽ tăng sát thương gây ra thêm 1. Nâng cấp vũ khí lần cuối sẽ có hiệu ứng đẩy lùi khi tấn công.
- Dưới cùng của menu thông tin nhân vật là thanh kinh nghiệm. Kinh nghiệm nhận được khi đánh bại quái vật. Mỗi khi thanh kinh nghiệm đầy, người chơi sẽ được lên cấp, tăng máu tối đa và hồi đầy thanh máu.
- Bên trên menu thông tin có một nút màu đỏ có tên "màn hình chính", bấm vào sẽ chuyển cảnh về màn hình menu trò chơi.



Giới thiệu màn chơi:
- Màn chơi 1: Nhiệm vụ của màn này là đi qua cánh cổng không gian để đến màn 2. Cổng sẽ bị khóa khi người chơi chưa đủ kinh nghiệm. Khi tương tác với cổng lúc này sẽ hiện lên thông báo "Bạn chưa đủ điểm kinh nghiệm. Hãy đánh bại quái vật để qua cổng." Có một con quái ở bên trái màn hình, hãy đánh bại nó để có điểm kinh nghiệm và đi qua cổng.
- Màn chơi 2: Nhiệm vụ màn này là đánh bại con trùm trong một căn phòng. Ở màn này sẽ có một số bức tường đặc biệt có thể bị phá hủy để mở ra một con đường ẩn. Những bức tường này sẽ có họa tiết khác so với những bức tường bình thường. Con trùm ở màn này có sát thương cao và có khả năng tấn công đẩy lùi, người chơi nên nâng cấp vũ khí, đánh các con quái nhỏ khác để lấy về kinh nghiệm.



Nguồn ảnh, âm thanh:
- Các hiệu ứng âm thanh như tấn công, mất máu, ... : https://assetstore.unity.com/packages/audio/sound-fx/free-casual-game-sfx-pack-54116
- Nhạc nền trò chơi: https://assetstore.unity.com/packages/audio/music/casual-game-bgm-5-135943
- Model nhân vật, kiến trúc, vũ khí, ...: https://0x72.itch.io/16x16-dungeon-tileset
