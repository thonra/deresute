# エンドポイント一覧

[概要](general.md) でも説明したとおり、ホスト名は http://game.starlight-stage.jp/ である。

たとえば VersionCheck であれば http://game.starlight-stage.jp/load/check になる。

これは `ApiType` に記載されている情報の焼き直しである。

このリストはバージョンアップによって増減する可能性があるため注意する必要がある。

| ID  | ApiType.Type              | URL                                  |
|----:|---------------------------|--------------------------------------|
| 0   | VersionCheck              | load/check                           |
| 1   | SignUp                    | tool/signup                          |
| 2   | PaymentStart              | payment/start                        |
| 3   | PaymentCancel             | payment/cancel                       |
| 4   | PaymentFinish             | payment/finish                       |
| 5   | PaymentItemList           | payment/item_list                    |
| 6   | UpdateBirth               | payment/update_birth                 |
| 7   | Load                      | load/index                           |
| 8   | Tutorial                  | tutorial/update_step                 |
| 9   | MemberUnitEdit            | unit/edit                            |
| 10  | MemberUnitRename          | unit/rename                          |
| 11  | MemberFavoriteEdit        | favorite/edit                        |
| 12  | MemberFavoriteRename      | favorite/rename                      |
| 13  | MemberTraining            | training/reinforce                   |
| 14  | MemberTrainingTrainer     | training/reinforce_item              |
| 15  | MemberEvolve              | training/evolve                      |
| 16  | MemberExceed              | training/exceed                      |
| 17  | MemberSell                | member/sell                          |
| 18  | MemberProtect             | member/protect_card                  |
| 19  | MemberPotentialUp         | training/potential_up                |
| 20  | MemberPotentialInit       | training/potential_initialize        |
| 21  | MemberCardStorageList     | card_storage/storage_list            |
| 22  | MemberCardStorageChange   | card_storage/change_storage          |
| 23  | MemberCardStorageSetting  | card_storage/setting                 |
| 24  | MemberCardStorageCardList | card_storage/card_list               |
| 25  | StoryStart                | story/start                          |
| 26  | StoryReleaseEventStory    | story/open_v2                        |
| 27  | LiveList                  | live/music_list                      |
| 28  | LiveRanking               | live/get_live_detail_ranking         |
| 29  | LiveFriendList            | live/supporter                       |
| 30  | LiveStart                 | live/start                           |
| 31  | LiveEnd                   | live/end                             |
| 32  | LiveContinue              | live/continue_game                   |
| 33  | LivePreContinueProcess    | live/continue_pre_process            |
| 34  | LiveInterrupt             | live/interrupt                       |
| 35  | LiveSendLog               | live/send_log                        |
| 36  | LiveStartView             | live/start_view                      |
| 37  | LiveDiscardStart          | live/discard_start                   |
| 38  | LiveDiscardEnd            | live/discard_end                     |
| 39  | LiveStartRehearsal        | live/start_rehearsal                 |
| 40  | LiveEndRehearsal          | live/end_rehearsal                   |
| 41  | LiveLiveLot               | live/live_lot                        |
| 42  | RoomLoad                  | room/index                           |
| 43  | RoomChangeLoad            | room/change_room                     |
| 44  | RoomBuy                   | room/buy                             |
| 45  | RoomBuyStorage            | room/buy_to_storage                  |
| 46  | RoomBuyMusic              | room/buy_music                       |
| 47  | RoomSell                  | room/sell                            |
| 48  | RoomUpdate                | room/update                          |
| 49  | RoomLevelUpStart          | room/levelup                         |
| 50  | RoomLevelUpComplete       | room/levelup                         |
| 51  | RoomLevelUpStop           | room/levelup                         |
| 52  | RoomLevelUpCutTime        | room/levelup                         |
| 53  | RoomLike                  | room/add_like                        |
| 54  | RoomLikeHistory           | room/get_liked_history_list          |
| 55  | RoomOther                 | room/other                           |
| 56  | RoomDeliveryBoxReceive    | room/receive_parcel                  |
| 57  | RoomDeliveryBoxUpdate     | room/update_delivery_box             |
| 58  | RoomTicketBoardReceive    | room/receive_ticket                  |
| 59  | RoomTicketBoardUpdate     | room/update_ticket_board             |
| 60  | RoomVisitRandom           | room/random_visit                    |
| 61  | RoomExtendBox             | room/extend_box                      |
| 62  | RoomGiftUpdate            | room/update_gift                     |
| 63  | RoomGiftReceive           | room/receive_gift                    |
| 64  | RoomGivePresent           | gift/give_present                    |
| 65  | RoomMoveItem              | room/move_room_item                  |
| 66  | RoomUpdateSetting         | room/update_room_setting             |
| 67  | RoomFavoriteEdit          | room/edit                            |
| 68  | RoomReceiveAll            | room/receive_all_charge_item         |
| 69  | RoomIdolPresent           | room/receive_idol_present            |
| 70  | RoomMySetLoad             | room/get_layout                      |
| 71  | RoomMySetSave             | room/update_layout                   |
| 72  | RoomMySetDelete           | room/clear_layout                    |
| 73  | RoomMySetRename           | room/rename_layout                   |
| 74  | RoomMySetUpdate           | room/update_with_charge_items        |
| 75  | GachaLoad                 | gacha/index                          |
| 76  | GachaExe                  | gacha/exec                           |
| 77  | FriendTop                 | friend/top                           |
| 78  | FriendList                | friend/friend_list                   |
| 79  | FriendApplyingList        | friend/request_list                  |
| 80  | FriendApprovalList        | friend/approval_pending_list         |
| 81  | FriendSearch              | friend/searching_list                |
| 82  | FriendSearchFromId        | friend/search_by_id                  |
| 83  | FriendRequest             | friend/request                       |
| 84  | FriendRequestCancel       | friend/cancel_request                |
| 85  | FriendApproval            | friend/accept                        |
| 86  | FriendApprovalCancel      | friend/deny                          |
| 87  | FriendDelete              | friend/delete                        |
| 88  | FriendCommentList         | message/index                        |
| 89  | FriendCommentSend         | message/send                         |
| 90  | ItemUseRecovery           | item/use_item                        |
| 91  | AlbumLoad                 | album/index                          |
| 92  | ProfileLoad               | profile/get_profile                  |
| 93  | ProfileRename             | profile/rename                       |
| 94  | ProfileComment            | profile/update_comment               |
| 95  | ProfileUpdateSupporters   | profile/update_supporters            |
| 96  | PresentLoad               | present/index2                       |
| 97  | PresentReceive            | present/receive                      |
| 98  | PresentReceiveAll         | present/receive_all                  |
| 99  | PresentHistory            | present/history                      |
| 100 | ShopRecoverStamina        | shop/recover_stamina                 |
| 101 | ShopExpandBox             | shop/extend_box                      |
| 102 | ShopJewel                 | shop/buy_jewel_shop                  |
| 103 | ShopExtendCardStorage     | shop/extend_card_storage             |
| 104 | ExchangeShopList          | exchange_shop/exchange_list          |
| 105 | ExchangeShopItem          | exchange_shop/exchange_item          |
| 106 | DressShopList             | exchange_shop/exchange_list          |
| 107 | DressShopBuy              | exchange_shop/exchange_item          |
| 108 | PanelMissionGetReward     | panel_mission/get_reward             |
| 109 | MissionLoad               | mission_v2/index                     |
| 110 | MissionRewardExe          | mission_v2/get_reward                |
| 111 | EmblemEdit                | emblem/edit                          |
| 112 | ProducerRankTop           | producer_rank/index                  |
| 113 | ProducerRankRanking       | producer_rank/mo_p_ranking_list      |
| 114 | ProducerRankRankingInfo   | producer_rank/mo_p_rank_data         |
| 115 | AtaponTop                 | event/atapon/load                    |
| 116 | AtaponRanking             | event/atapon/ranking_list            |
| 117 | AtaponResult              | event/atapon/result_info             |
| 118 | CaravanTop                | event/caravan/load                   |
| 119 | CaravanExchange           | event/caravan/exchange               |
| 120 | MedleyTop                 | event/medley/load                    |
| 121 | MedleyRanking             | event/medley/ranking_list            |
| 122 | MedleyLiveLot             | event/medley/live_lot                |
| 123 | MedleyStart               | event/medley/start                   |
| 124 | MedleySetUnit             | event/medley/set_unit                |
| 125 | MedleyNext                | event/medley/next                    |
| 126 | MedleyLifeRecover         | event/medley/recover_life            |
| 127 | MedleyLiveBreak           | event/medley/live_break              |
| 128 | MedleyEnd                 | event/medley/end                     |
| 129 | PartyTop                  | event/party/load                     |
| 130 | PartyStart                | event/party/start                    |
| 131 | PartyMatchingExec         | event/party/matching_exec            |
| 132 | PartyResult               | event/party/result                   |
| 133 | PartyEnd                  | event/party/end                      |
| 134 | TourTop                   | event/tour/load                      |
| 135 | TourRanking               | event/tour/ranking_list              |
| 136 | TourStart                 | event/tour/start                     |
| 137 | TourNext                  | event/tour/load                      |
| 138 | TourLiveBreak             | event/tour/load                      |
| 139 | TourEnd                   | event/tour/end                       |
| 140 | TourTitleRename           | event/tour/rename_tour               |
| 141 | EventDeck                 | event/party/unit_edit                |
| 142 | GossipAddUserTips         | tips/add_user_tips                   |
| 143 | MigrationUpdate           | migration/index                      |
| 144 | OptionUpdate              | option/update_guerrilla_notification |
| 145 | ScEx                      | premium_sc/ex_exec                   |
| 146 | NameCardLoad              | name_card/index                      |
| 147 | NameCardUpdate            | name_card/update                     |
| 148 | NameCardOther             | name_card/other                      |
| 149 | NameCardOtherList         | name_card/other_list                 |
| 150 | NameCardApply             | name_card/apply                      |
| 151 | NameCardRequestList       | name_card/request_list               |
| 152 | NameCardAccept            | name_card/accept                     |
| 153 | NameCardDeny              | name_card/deny                       |
| 154 | NameCardFavorite          | name_card/set_favorite               |
| 155 | NameCardDistribute        | name_card/distribute                 |
| 156 | NameCardDelete            | name_card/other_delete               |
| 157 | NameCardSetting           | name_card/setting                    |
| 158 | NameCardFavoriteCancel    | name_card/set_favorite_cancel        |
| 159 | NameCardAllApply          | name_card/all_apply                  |
| 160 | LotteryTopLoad            | lottery/load                         |
| 161 | LotteryGetReward          | lottery/receive                      |
| 162 | MemoryCacheClear          | test/memcache_flush                  |
| 163 | ManageUserInfo            | debug/manage_user_info               |
| 164 | DeleteAllPresent          | debug/delete_all_present             |
| 165 | UpdateItemList            | debug/update_item_list               |
| 166 | AddCardList               | debug/add_card_list                  |
| 167 | DeleteAllAlbum            | debug/delete_all_album               |
| 168 | AddAllAlbum               | debug/add_all_album                  |
| 169 | DebugUserReset            | debug/reset_all_data                 |
| 170 | DebugIdolUpdate           | debug/update_card_list               |
| 171 | DebugAddPresent           | debug/send_present_random            |