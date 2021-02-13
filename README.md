-- Adminer 4.2.1 MySQL dump

SET NAMES utf8;
SET time_zone = '+00:00';
SET foreign_key_checks = 0;
SET sql_mode = 'NO_AUTO_VALUE_ON_ZERO';

DROP TABLE IF EXISTS `bulmaca`;
CREATE TABLE `bulmaca` (
  `sira` int(11) NOT NULL AUTO_INCREMENT,
  `soru` varchar(255) DEFAULT NULL,
  `cevap` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`sira`)
) ENGINE=MyISAM;

INSERT INTO `bulmaca` (`sira`, `soru`, `cevap`) VALUES
(1,	'Abaküs',	'SAYIBONCUĞU'),
(2,	'Abartı',	'MÜBALAĞA'),
(3,	'ABD Başkanı Eisenhover\'in takma adı',	'İKE'),
(4,	'ABD de bir kent',	'ATLANTA, ŞİKAGO'),
(5,	'ABD Eyaletleri',	'NEBRASKA, NEVADA,NEW HAMRSHİRE,NEW JERSEY,NEW MEXİCO,NEW YORK,NORTH CAROLİNA,NORTH DAKOTA, OHİO, OKLAHAMA, OREGON, PENNZYLVANİA, RHODE İSLAND, SOUTH CAROLİNA, SOUTH DAKOTA,TENNESSEE,TEXAS,UTAH,VERMONT,VİRGİNİA,WASHİNGTON,WEST VİGİNİA,WİSCONSİN,WYOMİNG'),
(6,	'ABD Eyaletleri',	'ALABAMA, ALASKA, ARİZONA, ARKANSAS, CALİFORNİA, COLORADO, CONNECTİCUT, DELAWARE, FLORİDA, GEORGİA, HAWAİİ, İDAHO, İLLİNOİS, İNDİANA, İOWA, KANSAS, KENTUCKY, LOUİSİANA, MAİNE, MARYLAND, MASSACHUSETTS, MİCHİGAN, MİNNESOTA, MİSSİSSİPPİ, MİSSOURİ, MONTANA,'),
(7,	'ABD Profesyonel Basketbol ligi',	'NBA'),
(8,	'ABD Ulusal Havacılık ve Uzay Dairesi (kısaca)',	'NASA'),
(9,	'ABD\'de beş göllerden birisi',	'ERİE'),
(10,	'ABD\'nin Başkenti',	'WASHİNGTON D.C.'),
(11,	'ABD\'nin para birimi',	'DOLAR'),
(12,	'ABD\'nin uluslar arası plaka işareti',	'USA'),
(13,	'Abece',	'ALFABE'),
(14,	'Aberasyon',	'SAPINÇ'),
(15,	'Abes',	'SAÇMA'),
(16,	'Abi',	'AĞABEY'),
(17,	'Abide',	'ANIT'),
(18,	'Abidevi',	'ANITSAL'),
(19,	'Abıhayat',	'BENGİSU'),
(20,	'Abla',	'BACI'),
(21,	'Abuhava',	'İKLİM'),
(22,	'AC simgeli element',	'AKTİNYUM'),
(23,	'Acar',	'ÇALIŞKAN'),
(24,	'Acele',	'İVEDİ'),
(25,	'Acele Posta Servisi \"kısaca\"',	'APS'),
(26,	'Aceleci, acul',	'EVECEN, İVECEN'),
(27,	'Acelecilik',	'TELAŞ'),
(28,	'Acem',	'İRANLI'),
(29,	'Acemi',	'TOY'),
(30,	'Acemilik',	'TOYLUK'),
(31,	'Acı',	'IZDIRAP, KEDER'),
(32,	'Acı sesler çıkarmak',	'İNLEMEK'),
(33,	'Acı, üzüntü',	'ELEM'),
(34,	'Acıbadem ağacı',	'EREZ'),
(35,	'Acıbalık ta denilen bir tatlı su balığı',	'GÖRDEK'),
(36,	'Acıklı',	'ELİM'),
(37,	'Acıklı olay',	'DRAM'),
(38,	'Acıklı sahne oyunu',	'DRAM'),
(39,	'Acil',	'İVEDİ'),
(40,	'Acılar karşısında dayanma gücünü yitirmeyen, sağlam, dayanıklı, metanetli',	'METİN'),
(41,	'Acıma',	'MERHAMET'),
(42,	'Acımasız',	'ZALİM'),
(43,	'Acımasız, zorba',	'CEBERUT, CEBERRÜT'),
(44,	'Acımtırak bir içki',	'AMER'),
(45,	'Acının unutulması ya da hafiflemesi, teselli',	'AVUNÇ'),
(46,	'Acıyarak ve koruyarak seven, şefkatli',	'SEVECEN'),
(47,	'Aciz',	'GÜÇSÜZ, ZAYIF'),
(48,	'Acizler, güçsüzler',	'ACEZE'),
(49,	'Acun',	'DÜNYA'),
(50,	'Aç',	'HARİS'),
(51,	'Aç gözlü, hırslı',	'HARİS'),
(52,	'Aç gözlülük',	'TAMAH'),
(53,	'Aç olma durumu',	'AÇLIK'),
(54,	'Açacak',	'TİRBİŞON'),
(55,	'Açar',	'APERİTİF'),
(56,	'Açar',	'ANAHTAR'),
(57,	'Açı',	'ZAVİYE'),
(58,	'Açı ölçer',	'İLETKİ, MİNKALE'),
(59,	'Açı ölçmede kullanılan dönme hareketli cetvel',	'ALİDAT'),
(60,	'Açık',	'ALENİ'),
(61,	'Açık artırım ile satış',	'MEZAT'),
(62,	'Açık deniz',	'ENGİN'),
(63,	'Açık duran baş parmağın ucundan gösterme parmağının ucuna kadar olan uzaklık',	'SERE'),
(64,	'Açık elle vurulan tokat',	'ŞAMAR'),
(65,	'Açık havada çıkan kuru soğuk',	'AYAZ'),
(66,	'Açık leylak rengi',	'LİLA'),
(67,	'Açık mavi gözlü',	'MAVİŞ'),
(68,	'Açık olma durumu, açıklık',	'ALENİYET'),
(69,	'Açık saman rengi',	'KREM'),
(70,	'Açık sarı renk',	'LİMONİ, SAMANİ'),
(71,	'Açık su kanalı',	'ARK'),
(72,	'Açık toprak rengi',	'BOZ'),
(73,	'Açık yer, meydan, alan',	'SAHA'),
(74,	'Açık zincirli organik madde',	'ALİFATİK'),
(75,	'Açık, apaçık, belli',	'AŞİKAR'),
(76,	'Açık, net',	'BERRAK'),
(77,	'Açık, ortada, meydanda, herkesin içinde yapılan',	'ALENİ'),
(78,	'Açıkca, belirgin',	'AŞİKAR'),
(79,	'Açıkça gizlemeden',	'ALENEN'),
(80,	'Açıkça görünürlük, bellilik',	'BEDAHET'),
(81,	'Açıkça, gizlemeden, meydanda',	'ALENİ'),
(82,	'Açıkgöz',	'UYANIK'),
(83,	'Açıkgözlülük, hırs',	'TAMAH'),
(84,	'Açıklama',	'İZAH'),
(85,	'Açıklamalar',	'İZAHAT'),
(86,	'Açıklık',	'ALANİYET, ALENİLİK'),
(87,	'Açıklık ve boş arazi, sahra',	'KIR'),
(88,	'Açıktan açığa, herkesin gözü önünde, herkesin içinde, gizlemeden, açıkça',	'ALENEN'),
(89,	'Açılır kapanır perde türü',	'STOR'),
(90,	'Açkı',	'ANAHTAR'),
(91,	'Açma aracı',	'AÇACAK'),
(92,	'Ad',	'ÜN, İSİM, NAM'),
(93,	'Ad belirtilerek yapılan',	'NOMİNAL, YOKLAMA'),
(94,	'Ad çekme',	'KURA'),
(95,	'Ad ve Soyadın baş harfleriyle atılan kısa imza',	'PARAF'),
(96,	'Adaçayı',	'MERYEMİYE'),
(97,	'Adak',	'NEZİR'),
(98,	'Adakta bulunma',	'ADAMA'),
(99,	'Adale',	'KAS'),
(100,	'Adalet',	'HAK, TÜRE'),
(101,	'Adaletle iş gören, adaletten ayrılmayan',	'ADİL'),
(102,	'Adaletli',	'ADİL'),
(103,	'Adam öldürme',	'CİNAYET'),
(104,	'Adamak',	'NEZRETMEK'),
(105,	'Adana\'nın İlçeleri',	'SEYHAN, YÜREĞİR, ALADAĞ, BAHÇE, CEYHAN, DÜZİÇİ, FEKE, İMAMOĞLU, KADİRLİ, KARAİSALI, SAİMBEYLİ, TUĞFANBEYLİ, YUMURTALIK'),
(106,	'Adavet',	'DÜŞMANLIK'),
(107,	'Aday',	'NAMZET'),
(108,	'Adcılık',	'NOMİNALİZM'),
(109,	'Adem ile Hava\'nın üçüncü oğlu',	'ŞİT'),
(110,	'Ademiyat',	'BEŞERİYET, İNSANİYET, İNSANLIK'),
(111,	'Ademoğlu, beşer',	'İNSAN'),
(112,	'Adese',	'LUP, MERCEK'),
(113,	'Adet',	'TANE'),
(114,	'Adet haline getirme, alışma, alışkanlık',	'İTİYAT'),
(115,	'Adet, parça',	'PARE'),
(116,	'Adi',	'BAYAĞI, DEĞERSİZ, KABA, ÖZENSİZ'),
(117,	'Adı sanı belli olmayan',	'ANONİM'),
(118,	'Adil',	'ADALETLİ'),
(119,	'Adıl',	'ZAMİR'),
(120,	'Adım aralığı',	'FULE'),
(121,	'Adın durum elerinden biri',	'DE'),
(122,	'Adını anma',	'ZİKİR'),
(123,	'Adıyaman\'ın İlçeleri',	'BESNİ, ÇELİKHAN, GERGER, GÖLBAŞI, KAHTA, SAMSAT, SİNCİK, TUT'),
(124,	'Adiyö',	'HOŞCAKAL'),
(125,	'Adlar, isimler',	'ESAME'),
(126,	'Adları aynı olanlardan her biri',	'ADAŞ'),
(127,	'Adli',	'TÜREL'),
(128,	'Adolf Hitler\'in partisi',	'NAZİ'),
(129,	'Af',	'BAĞIŞLAMA'),
(130,	'Afacan',	'YARAMAZ'),
(131,	'Afak',	'UFUKLAR'),
(132,	'Afakiye',	'NESNELCİLİK'),
(133,	'Aferin',	'BRAVO'),
(134,	'Afete uğramış',	'AFETZEDE'),
(135,	'Affetmek',	'BAĞIŞLAMAK'),
(136,	'Afganistan\'da bir şehir',	'HERAT'),
(137,	'Afganistan\'ın Başkenti',	'KABİL'),
(138,	'Afganistan\'ın para birimi',	'AFGANİ'),
(139,	'Afi',	'CAKA, FİYAKA'),
(140,	'Afitap',	'GÜNEŞ'),
(141,	'Afiyet',	'SAĞLIK'),
(142,	'Aforizma',	'ÖZDEYİŞ'),
(143,	'Afrika misk kedisi',	'KALEMİKS'),
(144,	'Afrika Ulusal Kongresi\'ni simgeleyen harfler',	'ANC'),
(145,	'Afrika yerli davulu',	'TAMTAM'),
(146,	'Afrika\'da bir akarsu',	'NİL'),
(147,	'Afrika\'da yaşayan bir tür antilop',	'KOB'),
(148,	'Afrika\'da yaşayan, gövdesi kızıl kestane, bacakları beyaz çizgili memeli hayvan',	'OKAPİ'),
(149,	'Afrika\'nın en yüksek dağı Kilimanjaro\'nun, yerli dillerde \"özgürlük\" anlamına gelen yeni adı',	'UHURU'),
(150,	'Afrika\'nın hızlı koşullar için yetiştirilmiş evcil hecin devesi',	'MEHARİ'),
(151,	'Afrika\'nın kimi yerlerinde toplu biçimde yapılan vahşi hayvan acı',	'SAFARİ'),
(152,	'Afrika\'ya hayat veren akarsu',	'NİL'),
(153,	'Afrikalı zencilerin büyük bir bölümünü içine alan etnik grup',	'BANTU'),
(154,	'Afyon\'un İlçeleri',	'BAŞMAKÇI, BAYAT, BOLVADİN, ÇAY, ÇOBANLAR, DAZKIRI, DİNAR, EMİRDAĞ, EVCİLER, HOCALAR, İHSANİYE, İSCEHİSAR, KIZILÖREN, SANDIKLI, SİNCANLI, SULTANDAĞI, ŞUHUT'),
(155,	'AG simgeli element',	'GÜMÜŞ'),
(156,	'Ağ',	'ŞEBEKE'),
(157,	'Ağ şeklinde yapılan örgü',	'FİLE'),
(158,	'Ağ tabaka',	'RETİNA'),
(159,	'Ağ torba',	'FİLE'),
(160,	'Ağ yatak',	'HAMAK'),
(161,	'Ağabey',	'ABİ, AKA'),
(162,	'Ağabey (kısaca)',	'ABİ'),
(163,	'Ağabey sözcüğünün kısa söyleniş biçimi',	'ABİ'),
(164,	'Ağabeyin eşi',	'YENGE'),
(165,	'Ağacı çizmeye yarayan çember kesitli, ucu sivri ve ağaç saplı el aracı',	'ÇİZECEK'),
(166,	'Ağacın gövdesinden ayrılan kollardan her biri',	'DAL'),
(167,	'Ağaçlarla örtülü alan',	'ORMAN'),
(168,	'Ağaçlıklı yol',	'ALE'),
(169,	'Ağan',	'AKANYILDIZ, ŞAHAP'),
(170,	'Ağdalık',	'VİSKOZİT'),
(171,	'Ağı',	'ZEHİR'),
(172,	'Ağı, sem',	'ZEHİR'),
(173,	'Ağıağacı',	'ZAKKUM'),
(174,	'Ağıl',	'DAM, KOM'),
(175,	'Ağılı',	'ZEHİRLİ'),
(176,	'Ağır bir dans türü',	'SLOV'),
(177,	'Ağır ritimli bir İspanyol dansı',	'BOLERO'),
(178,	'Ağır topuz',	'GÜRZ'),
(179,	'Ağır, sert ve siyah renkli tahtası olan ağaç',	'ABANOZ'),
(180,	'Ağırbaşlı, onurlu',	'VAKUR'),
(181,	'Ağırlama',	'İZAZ'),
(182,	'Ağırlık',	'YÜK'),
(183,	'Ağırlık ölçmekte kullanılan alet',	'TERAZİ'),
(184,	'Ağırlık ve uzunluk ölçüleri için kabul edilmiş kanuni ölçü modeli',	'ETALON'),
(185,	'Ağırlık yitimi',	'FİRE'),
(186,	'Ağıt',	'ELEJİ'),
(187,	'Ağız ağıza dolu, ağzına kadar dolu, silme',	'LEBALEB'),
(188,	'Ağız armonikası',	'MIZIKA'),
(189,	'Ağız boşluğunun tavanı',	'DAMAK'),
(190,	'Ağızda evirip çevirme',	'GEVELEME'),
(191,	'Ağızdan çıkan, bir veya daha fazla heceden meydana gelen ve mana ifade eden kelime veya kelime topluluğu',	'SÖZ'),
(192,	'Ağızdan, sözle söylenerek',	'ŞİFAHEN'),
(193,	'Ağlayan, inleyen',	'NALAN'),
(194,	'Ağrı dağının eski adı',	'ARARAT'),
(195,	'Ağrı\'nın İlçeleri',	'DİYADİN, DOĞUBEYAZIT, ELEŞKİRT, HAMUR, PATNOS, TAŞLIÇAY, TUTAK'),
(196,	'Ağtabaka',	'RETİNA'),
(197,	'Ağzı çember biçiminde, torbaya benzer büyük gözlü ağ',	'APOSİ'),
(198,	'Ağzı dar, şişkin gövdeli su kabı',	'DAMACANA'),
(199,	'Ağzı geniş tek kulplu su kabı',	'KANATA'),
(200,	'Ağzı sıkı',	'KETUM'),
(201,	'Ağzı sıkılık',	'KETUMİYET'),
(202,	'Ağzı yayvan toprak kap',	'DAGAR'),
(203,	'Ağzın tavanı',	'DAMAK'),
(204,	'Ağzına kadar dolu',	'LEBELEB, TIKABASA'),
(205,	'Ah',	'BEDDUA, İLENÇ, İLENME'),
(206,	'Ahali',	'AVAM, HALK'),
(207,	'Ahenk',	'UYUM'),
(208,	'Ahenk, ölçü, düzenlilik',	'RİTİM'),
(209,	'Ahenksiz',	'UYUMSUZ'),
(210,	'Ahilik ocağından olan kimse',	'AHİ'),
(211,	'Ahır',	'DAM'),
(212,	'Ahırdaki iki hayvan yeri arasında bölme olarak kullanılan kalın sırık',	'ARALTI'),
(213,	'Ahirette bütün insanların üzerinden geçeceği köprü',	'SIRAT'),
(214,	'Ahize',	'ALICI, ALMAÇ'),
(215,	'Ahmak, sersem',	'SEME'),
(216,	'Ahret ile ilgili',	'UHREVİ'),
(217,	'Ahşap gemilerin omurgalarına, borda kaplamalarını yerleştirmek için açılan yuva',	'AŞOZ'),
(218,	'Aidat',	'ÖDENTİ'),
(219,	'AİDS Testi',	'ELİZA'),
(220,	'Aile',	'FAMİLYA'),
(221,	'Aile halkı',	'HORANTA'),
(222,	'Aile ile ilgili',	'AİLEVİ'),
(223,	'Aile ocağı',	'YUVA'),
(224,	'Ailesinin geçimini sağlayan',	'AİL'),
(225,	'Ait',	'DEĞİN, İLİŞKİN'),
(226,	'Ait olma durumu, ilişkinlik, aitlik, dairlik',	'AİDİYET'),
(227,	'Ajan',	'CASUS'),
(228,	'Ak',	'BEYAZ, LEKESİZ, NAMUSLU, TEMİZ'),
(229,	'Ak tenli mavi gözlü kimse',	'MAVİŞ'),
(230,	'Aka',	'AĞABEY'),
(231,	'Akaç',	'DİREN'),
(232,	'Akademik bir unvan',	'PROFESÖR'),
(233,	'Akademik unvan',	'DR'),
(234,	'Akaju da denilen bir ağaç',	'MAUN'),
(235,	'Akamet',	'SONUÇSUZLUK, VERİMSİZLİK'),
(236,	'Akanyıldız',	'AĞAN, ŞAHAP'),
(237,	'Akarsu',	'IRMAK, NEHİR'),
(238,	'Akarsu kıyılarındaki çalı ve ağaçların üzerinde de yaşayabilen bir balık',	'ANABAS'),
(239,	'Akarsu üzerinde yapılan bent',	'BARAJ'),
(240,	'Akarsu yatağı, mecra',	'AKAK'),
(241,	'Akarsuyun saniyelik akımı',	'DEBİ'),
(242,	'Akciğer',	'RİE'),
(243,	'Akciğer (eski dil)',	'RİE'),
(244,	'Akdeniz Anemisi adı da verilen bir hastalık',	'TALASEMİ'),
(245,	'Akdeniz Bölgesi\'nde turistik bir koy',	'OKLUK'),
(246,	'Akdeniz bölgesinin kısa boylu tipik bitki örtüsü',	'MAKİ'),
(247,	'Akdeniz havzasında görülen çok sıcak bir rüzgar',	'SİROKO'),
(248,	'Akdeniz tipi bitki örtüsü',	'MAKİ'),
(249,	'Akdeniz\'de bir ada',	'GİRİT, RODOS'),
(250,	'Akdeniz\'de bir ada ülkesi',	'MALTA'),
(251,	'Akdeniz\'de hapishanesi ile ünlü küçük bir Fransız adası',	'İF'),
(252,	'Ake',	'DİVİT'),
(253,	'Akı',	'AKINTI, AKMA, SEYELAN'),
(254,	'Akıcı',	'AKAR, LİKİT, MAYİ, SIVI'),
(255,	'Akıl',	'US'),
(256,	'Akıl ve gerçeğe aykırı',	'ABES'),
(257,	'Akilane',	'AKILLICA'),
(258,	'Akıllı',	'AKİL, USLU, ZEKİ'),
(259,	'Akıllı, akıl sahibi',	'AKİL'),
(260,	'Akıllıca',	'AKİLANE'),
(261,	'Akılsız',	'BUDALA, EBLEH'),
(262,	'Akim',	'BAŞARISIZ, SONUÇSUZ, VERİMSİZ'),
(263,	'Akım',	'CEREYAN'),
(264,	'Akımtoplar',	'AKÜ'),
(265,	'Akın',	'HÜCUM'),
(266,	'Akıntı',	'AKI, AKMA, SEYELAN'),
(267,	'Akis',	'AKS, EKO, YANKI'),
(268,	'Akit',	'KONTRAT, MUKAVELE, MUKAVELENAME, NİKAH, SÖZLEŞME'),
(269,	'Akıtma',	'İSALE'),
(270,	'Akkan',	'LENF'),
(271,	'Akla ve gerçeğe aykırı',	'ABES'),
(272,	'Aklama',	'İBRA'),
(273,	'Aklama, temize çıkma',	'İBRA'),
(274,	'Aklanmış',	'BERAAT'),
(275,	'Akli',	'USSAL'),
(276,	'Aklı dengesi yerinde olmayan',	'DELİ'),
(277,	'Aklımda denen oyun',	'LADES'),
(278,	'Aklıselim',	'SAĞDUYU'),
(279,	'Akma',	'AKI, AKINTI, REÇİNE, SEYELAN,'),
(280,	'Akort oluşturan seslerin bir biri arkasından çalınması',	'ARPEJ'),
(281,	'Akraba',	'HISIM'),
(282,	'Akran',	'DENK, ÖĞÜR, YAŞIT'),
(283,	'Akrobat',	'CAMBAZ'),
(284,	'Aks',	'AKİS, DİNGİL, EKO, ROT, YANKI,'),
(285,	'Aksak',	'TOPAL, LENG'),
(286,	'Aksaklığı olan',	'ARIZALI'),
(287,	'Aksama, aksaklık',	'ARIZA'),
(288,	'Aksaray İlinde yamaçlarında birçok manastır, kilise, peribacaları ve koniler bulunan vadi',	'IHLARA VADİSİ'),
(289,	'Aksaray\'ın İlçeleri',	'AĞAÇÖREN, ESKİL, GÜLAĞAÇ, GÜZELYURT, ORTAKÖY, SARIYAHŞİ'),
(290,	'Aksata',	'ALIŞVERİŞ'),
(291,	'Aksayan, işlemeyen, bozulmuş',	'ARIZALI'),
(292,	'Aksetme, yansıma, yankılanma',	'İNİKAS'),
(293,	'Aksi, ters',	'TERS, ZIT'),
(294,	'Aksilik',	'TERSLİK'),
(295,	'Aksiseda, yankı',	'EKO'),
(296,	'Akşam namazı',	'AŞA'),
(297,	'Aktar',	'BAHARATÇI'),
(298,	'Aktar\'ın sattığı şeyler, aktar eşyası',	'AKTARİYE'),
(299,	'Aktarma',	'VİRMAN'),
(300,	'Aktif',	'CANLI, ETKEN, ETKİN, FAAL'),
(301,	'Aktörün sahnedeki işi',	'ROL'),
(302,	'Akü',	'AKIMTOPLAR'),
(303,	'Akyuvar',	'LOKOSİT'),
(304,	'Al',	'HİLE, KIRMIZI'),
(305,	'Al Salvador\'un Başkenti',	'SAN SALVADOR'),
(306,	'AL simgeli element',	'ALÜMİNYUM'),
(307,	'Alabalıkgiller familyasından, denizlerde yaşayan bir balık türü',	'DENİZANASI'),
(308,	'Alacak',	'BORÇ, MATLUP, TAKANAK'),
(309,	'Alacak ya da borç',	'TAKANAK'),
(310,	'Alaka',	'İLGİ'),
(311,	'Alakadar',	'ALAKALI'),
(312,	'Alakalı',	'ALAKADAR'),
(313,	'Alakok',	'RAFADAN'),
(314,	'Alalama',	'KAMUFLE'),
(315,	'Alamet',	'İM, İZ'),
(316,	'Alan',	'MEYDAN, SAHA,'),
(317,	'Alanı geniş',	'İHATALI'),
(318,	'Alaniyet',	'AÇIKLIK'),
(319,	'Alanya\'nın tarihteki adı',	'ALAİYE'),
(320,	'Alaşit',	'HALİTA'),
(321,	'Alaten',	'CÜZZAMLI'),
(322,	'Alaturka karşıtı',	'ALAFRANGA'),
(323,	'Alaturka Müzik kurallarını inceleyen yapıt',	'EDVAR'),
(324,	'Alay',	'İSTİHZA, KALABALIK, SARAKA'),
(325,	'Alay işareti',	'NANİK'),
(326,	'Alay, istihza',	'SARAKA'),
(327,	'Alayiş',	'GÖSTERİŞ'),
(328,	'Alaz',	'ALEV, YALAZ, YALAZA'),
(329,	'Albay',	'MİRALAY'),
(330,	'Albüm',	'RESİMLİK'),
(331,	'Alçak',	'NAMERT'),
(332,	'Alçak gönüllü olan, titizlik göstermeyen',	'KALENDER'),
(333,	'Alçak gönüllü, uysal',	'TEVAZULU'),
(334,	'Alçak gönüllülük',	'TEVAZU'),
(335,	'Alçak, aşağılık, kötü',	'REZİL'),
(336,	'Alçak, kötü kimse',	'DENİ'),
(337,	'Alçalma, düşkünlük',	'ZİL'),
(338,	'Aldatma',	'DESİSE, DÜZEN, OYUN'),
(339,	'Aldatma işi',	'AL, DEK, DOLAP, HİLE'),
(340,	'Aldırışsız, umursamaz',	'LAKAYT'),
(341,	'Aleladelik',	'SIRADANLIK'),
(342,	'Alem',	'BAYRAK, CİHAN, KAİNAT'),
(343,	'Alemdar',	'BAYRAKTAR, SANCAKTAR'),
(344,	'Alemşümul',	'EVRENSEL'),
(345,	'Aleni',	'AÇIK'),
(346,	'Alenilik',	'AÇIKLIK'),
(347,	'Alerjilerin tedavisini konu alan bilim dalı',	'ALERGOLOJİ'),
(348,	'Aletler bütünü',	'MAKİNE'),
(349,	'Aletler, araçlar',	'LEVAZIM'),
(350,	'Aleut takımadalarında yer alan adalar',	'RAT'),
(351,	'Alev',	'ALAZ, YALIM'),
(352,	'Alev, alev dili',	'YALAZA'),
(353,	'Alev, yalım',	'ŞULE'),
(354,	'Aleve tutmak',	'ALAZLAMAK'),
(355,	'Alevi-Bektaşi ozanlarının tarikatlarıyla ilgili şiirlerine verilen ad',	'DEME'),
(356,	'Alfabe',	'ABECE'),
(357,	'Algı',	'İDRAK'),
(358,	'Alicenap',	'CÖMERT'),
(359,	'Alıcı',	'AHİZE'),
(360,	'Alıcı kan grubu',	'AB'),
(361,	'Alıcı yönetmeni',	'KAMERAMAN'),
(362,	'Alıcı, reseptör',	'AHİZE'),
(363,	'Alıklaşma',	'APTAL'),
(364,	'Alil',	'SAKAT'),
(365,	'Alim',	'BİLGİN'),
(366,	'Alım, çekicilik, cazibe',	'ALBENİ'),
(367,	'Alın yazısı',	'FATALİTE'),
(368,	'Alın yazısı, takdir',	'KADER'),
(369,	'Alın yazısı, yazgı',	'FATALİTE, KADER'),
(370,	'Alınan bir şeyi geri verme',	'İADE'),
(371,	'Alinan bir şeyi geri verme',	'İADE'),
(372,	'Alınma',	'GÜCENME'),
(373,	'Alınması gereken şey',	'ALACAK'),
(374,	'Alınmış bir şeyi geri verme',	'İADE'),
(375,	'Alıntı',	'İKTİBAS'),
(376,	'Alışılagelen',	'RUTİN'),
(377,	'Alışılan zamandan önce',	'ER, ERKEN'),
(378,	'Alışılandan fazla',	'BOL'),
(379,	'Alışılmış, alışılan',	'MUTAT'),
(380,	'Alışkanlık halinde yapılan',	'RUTİN'),
(381,	'Alışkanlık, huy',	'İTİYAT'),
(382,	'Alışma',	'ÜLFET'),
(383,	'Alışveriş',	'AKSATA'),
(384,	'Alışverişte durgunluk hali, sürümsüzlük',	'KESAT'),
(385,	'Alışverişte kötü mal satmak',	'KAKALAMAK'),
(386,	'Alkol',	'ETANOL'),
(387,	'Alkol ve Madde bağımlıları Tedavi Merkezi (kısaca)',	'AMATEM'),
(388,	'Alkolde eriyen hayvansal reçine',	'GOMALAK'),
(389,	'Alkollü bir içki',	'CİN, ŞARAP, VOTKA'),
(390,	'Allah (cc) velilerinden zuhur eden olağanüstü hal, harikulade hal',	'KERAMET'),
(391,	'Allah (cc)\'a kalbi bağlılık, kesin inanma; iman',	'İTİKAT'),
(392,	'Allah (cc)\'a karşı kulluk vazifesini yetirme getirme, tapınma',	'İBADET'),
(393,	'Allah (cc)\'a ve İslâm akidelerine inanma',	'İMAN'),
(394,	'Allah (cc)\'a ve O\'nun rızasına erişmek için tutulan yol, tasavvuf yolu',	'TARİKAT'),
(395,	'Allah (cc)\'ın bir kimseye insanı',	'İNAYET'),
(396,	'Allah (cc)\'ın emirlerine tam itaat eden yaratık, ferişteh',	'MELEK'),
(397,	'Allah (cc)\'ın isimlerinden biri',	'RAM'),
(398,	'Allah (cc)\'ın kullarına ve diğer yaratıklarına lütfu olan nimet, yenilen, içilen ve sarf edilen şey, kısmet',	'RIZIK'),
(399,	'Allah (cc)\'ın sıfatlarından biri',	'RAHİM'),
(400,	'Allah (cc)\'ın sıfatlarından; lutfu ve ihsanı bol',	'KERİM'),
(401,	'Allah (cc)\'ın, fazlasıyla merhametli ve esirgeyici anlamına gelen sıfatı',	'RAUF'),
(402,	'Allah\'ı tanımayan',	'KAFİR'),
(403,	'Alma',	'FETHETME'),
(404,	'Almaç',	'AHİZE'),
(405,	'Alman Faşisti',	'NAZİ'),
(406,	'Alman markının yüzde biri',	'FENİK'),
(407,	'Almanca \"Bir\"',	'EİN'),
(408,	'Almanca \"Evet\"',	'JA'),
(409,	'Almanca \"Sen\"',	'DU'),
(410,	'Almanca \"Ve\"',	'UND'),
(411,	'Almanya\'da bin kent',	'AEREN'),
(412,	'Almanya\'da bir eyalet',	'SAAR'),
(413,	'Almanya\'da bir ırmak',	'WUPPER'),
(414,	'Almanya\'da bir kent',	'AACHEN, BREMEN'),
(415,	'Almanya\'nın eski para biriminin kısa yazılışı',	'DM'),
(416,	'Almanya\'nın para birimi',	'MARK'),
(417,	'Alp',	'CİVANMERT, ER, YİĞİT'),
(418,	'Alt alta yazılmış şeyler',	'LİSTE'),
(419,	'Alt karşıtı',	'ÜST'),
(420,	'Alt kurul, encümen',	'KOMİTE'),
(421,	'Alt, aşağı',	'ZİR'),
(422,	'Altar',	'SUNAK'),
(423,	'Alternatif',	'SEÇENEK'),
(424,	'Altı düz, geniş ve sağlam yapılı tekne',	'LAYTER'),
(425,	'Altı Mayıs\'ta yapılan geleneksel bayram',	'HIDRELLEZ'),
(426,	'Altı yüzlü dikdörtgen',	'KÜP'),
(427,	'Altıkardeş takım yıldızı',	'ZATÜLKÜRSİ'),
(428,	'Altın',	'ZER'),
(429,	'Altın ve Gümüş işlemeli bir tür ipek kumaş',	'DİBO'),
(430,	'Altın, gümüş gibi madenlerden yapılmış şeylerin saflık derecesi',	'AYAR'),
(431,	'Altının latince adı',	'AİRUM'),
(432,	'Altınkökü',	'İPEKA'),
(433,	'Altmış beş santimetre boyunda bir uzunluk ölçüsü',	'ENDAZE'),
(434,	'Altmış dakikalık zaman birimi',	'SAAT'),
(435,	'Altmış saniye',	'DAKİKA'),
(436,	'Alüvyon',	'LIĞ'),
(437,	'Alyuvar',	'ERİTROSİT'),
(438,	'AM simgeli element',	'AMERİSYUM'),
(439,	'Ama',	'DARİR, GÖRMEZ, KÖR'),
(440,	'Ama, fakat, ancak',	'LAKİN'),
(441,	'Amaç',	'EREK, GAYE'),
(442,	'Amaç, gaye',	'EREK'),
(443,	'Amaç, maksat',	'GAYE'),
(444,	'Amaçsız',	'GAYESİZ'),
(445,	'Amade',	'ANIK, HAZIR'),
(446,	'Amasya\'nın İlçeleri',	'GÖYNÜCEK, GÜMÜŞHACIKÖY, HAMAMÖZÜ, MERZİFON, SULUOVA, TAŞOVA'),
(447,	'Amatör olma durumu',	'AMATÖRLÜK'),
(448,	'Ambar',	'KİLER'),
(449,	'Amca',	'EMMİ'),
(450,	'Amel',	'DİYARE, İSHAL, ÖTÜRÜK, SÜRGÜN'),
(451,	'Amel',	'İŞ'),
(452,	'Amele',	'İŞÇİ'),
(453,	'Amelelik',	'İŞÇİLİK'),
(454,	'Ameliyat yapan hekim, cerrah',	'OPERATÖR'),
(455,	'Amerika Birleşik Devletleri (kısaca)',	'ABD'),
(456,	'Amerika Birleşik Devletleri halkından olan kimse',	'AMERİKALI'),
(457,	'Amerika kabilelerinden bazılarının Hindistan cevizi suyunu kaynatıp yaptıkları içki',	'ORRAKA'),
(458,	'Amerikalı',	'YANKİ'),
(459,	'Amerikan armudu da denilen bir meyve',	'AVUKADO'),
(460,	'Amerikan devesi',	'LAMA'),
(461,	'Amerikan istihbarat teşkilatı',	'FBİ'),
(462,	'Amerikan pamuğu',	'AKALA'),
(463,	'Amerikan uzay örgütü (kısaca)',	'NASA'),
(464,	'Amil',	'ETKEN, ETMEN, FAKTÖR'),
(465,	'Amil',	'ETKİN'),
(466,	'Amiral yetkisiyle görevli deniz subayı',	'KOMODOR'),
(467,	'Amiralden bir rütbe küçük deniz subayı',	'VİSAMİRAL'),
(468,	'Amirler',	'ÜMERA'),
(469,	'Amme',	'KAMU'),
(470,	'Amonyak tuzu',	'NIŞADIR'),
(471,	'Amorf',	'ŞEKİLSİZ'),
(472,	'Ampul yuvası',	'DUY'),
(473,	'An',	'LAHZA'),
(474,	'Ana',	'ANNE, ASIL, BAZ, ESAS, TEMEL, VALİDE'),
(475,	'Ana ile dölüt arasında kan alışverişini sağlayan organ',	'ETENE'),
(476,	'Ana para',	'KAPİTAL'),
(477,	'Ana, baba ve çocuklardan oluşan topluluk',	'AİLE'),
(478,	'Ana, esas',	'TEMEL'),
(479,	'Ana, temel',	'ESAS'),
(480,	'Anadolu Ajansı (kısaca)',	'AA'),
(481,	'Anadolu beyliklerinde donanmada kullanılan asker',	'AZAP'),
(482,	'Anadolu karasının batıdaki en uç noktası',	'BABABURUN'),
(483,	'Anadolu\'da hüküm sürmüş eski bir medeniyet',	'ETİ'),
(484,	'Anadolu\'nun birçok yöresinde ve düğünlerde yapılan güreşe verilen ad',	'GENCER'),
(485,	'Anadolu\'nun kapılarını Türk\'lere açan Selçuklu hükümdarı',	'ALPARSLAN'),
(486,	'Anafor',	'GİRDAP'),
(487,	'Anahtar',	'AÇAR, AÇKI'),
(488,	'Anahtarla açılan kapı düzeneği',	'KİLİT'),
(489,	'Analiz yapan kimse',	'ANALİST'),
(490,	'Analog karşıtı',	'DİJİTAL'),
(491,	'Anamal',	'KAPİTAL'),
(492,	'Anasına düşkün olan',	'ANACIL'),
(493,	'Anasır',	'UNSURLAR'),
(494,	'Anavatan',	'ANAYURT, ÖZYURT'),
(495,	'Anayoldan ayrılan yolun başlangıç noktası',	'SAPAK'),
(496,	'Anayurt',	'ANAVATAN, VATAN'),
(497,	'Andora\'nın Başkenti',	'ANDORRA LA VELLA');
