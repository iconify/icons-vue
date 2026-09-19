<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s68m5bbkm"/><path fill="url(#iArPqEq)" class="p0s-2mbfp"/><circle fill="url(#iZupPAb)" class="uz595pb0z"/><circle fill="url(#ipedU3b)" class="uz595pb0z"/><circle fill="url(#i68YR8c)" class="uz595pb0z"/><circle fill="url(#irccdIb)" class="uz595pb0z"/><circle fill="url(#iH4hoLb)" class="uz595pb0z"/><circle fill="url(#iEjMwPd)" class="r-44o0dxo"/><circle fill="url(#iomeuBc)" class="r-44o0dxo"/><circle fill="url(#iUyF4bd)" class="r-44o0dxo"/><circle fill="url(#irVLSRS)" class="r-44o0dxo"/><circle fill="url(#iimPrEP)" class="sm3quyfdj"/><circle fill="url(#iAH1cHd)" class="sm3quyfdj"/><circle fill="url(#iGzr9jc)" class="sm3quyfdj"/><circle fill="url(#iVgyjRb)" class="sm3quyfdj"/><path fill="url(#iTrS1ee)" class="chvrrkbvx"/><path fill="url(#iSJpcTb)" class="chvrrkbvx"/><path fill="url(#iugkz2b)" class="chvrrkbvx"/><path fill="url(#iXad0Mv)" class="chvrrkbvx"/><g filter="url(#iSgbKmN)" class="djts3zb8u"><path class="flzpcw40p"/><path stroke="url(#iITUWAc)" class="oporj11af"/></g><g filter="url(#iYNBX7d)"><path stroke="url(#iAMWAAc)" class="axifqjb6q"/></g><g filter="url(#ic3ll5d)" class="djts3zb8u"><path class="unwt0ub1f"/><path stroke="url(#ixDZOnd)" class="do_6cwmjy"/></g><g filter="url(#i0awTyx)"><path stroke="url(#i4nLYcb)" class="ancjbcimi"/></g><g filter="url(#iXwb0mb)" class="djts3zb8u"><path class="ry3kdy46i"/><path stroke="url(#ii1UA2d)" class="cg57ekzwo"/></g><g filter="url(#i8hVF1d)"><path stroke="url(#iJiC12b)" class="zlvwmnbye"/></g><g filter="url(#i8OxBGc)" class="djts3zb8u"><path class="y483f1bui"/><path stroke="url(#iNEkAzd)" class="m17uq_e5y"/></g><g filter="url(#i1Nc0Cb)"><path stroke="url(#iOff8we)" class="ck3k_wfle"/></g><g filter="url(#iIFk8rT)" class="djts3zb8u"><path class="c6lfh3b6m"/><path stroke="url(#i6DRWyb)" class="a0o5ylb4a"/></g><g filter="url(#iGF6Sde)"><path stroke="url(#iDgUvUb)" class="zpyr3xbsc"/></g><g filter="url(#ijVFUsc)" class="djts3zb8u"><path class="jla0qacrg"/><path stroke="url(#i6eMP3d)" class="h61yhotba"/></g><g filter="url(#im32yAY)"><path stroke="url(#ifgWgFe)" class="did7jilbi"/></g><path fill="url(#i2EJ1le)" class="nzb4st3-r"/><path fill="url(#i2O1dvc)" class="nzb4st3-r"/><path fill="url(#iuvYnAc)" class="nzb4st3-r"/><path fill="url(#icNgNxu)" class="nzb4st3-r"/><path fill="url(#imBi8eb)" class="nzb4st3-r"/><path fill="url(#iKejaKe)" class="nzb4st3-r"/><path fill="url(#iIj2VGe)" class="nzb4st3-r"/><path fill="url(#ipe3Rmc)" class="nzb4st3-r"/><path fill="url(#iZlExRd)" class="nzb4st3-r"/><g filter="url(#iA8KgGb)"><path class="qyi_zq9xe"/></g><g filter="url(#ij6EVUc)"><path fill="url(#ibB1vWn)" class="ec9dzrsdg"/></g><path class="bk6f83bgf"/><path fill="url(#i4p2f6b)" class="owewqybdc"/><path fill="url(#is5gZGc)" class="owewqybdc"/><path class="aaxcev0jp"/><path fill="url(#iTjdsCc)" class="itozaqcjq"/><path fill="url(#i9pBh9c)" class="itozaqcjq"/><path fill="url(#i1gIqkZ)" class="itozaqcjq"/><path fill="url(#iVTEErb)" class="itozaqcjq"/><g filter="url(#iJsMndc)"><path fill="url(#i96xMod)" class="olam3_b5n"/></g><path fill="url(#iL8eJ3b)" class="cv5r0l50t"/><path fill="url(#inQW4Jc)" class="cv5r0l50t"/><path fill="url(#i7W9nWE)" class="cv5r0l50t"/><path fill="url(#iUPWJRb)" class="cv5r0l50t"/><path fill="url(#il17ANd)" class="cv5r0l50t"/><path fill="url(#iWn2Xid)" class="cv5r0l50t"/><path fill="url(#i7nt9we)" class="cv5r0l50t"/><path fill="url(#ilWikue)" class="cv5r0l50t"/><path fill="url(#isZxfAb)" class="cv5r0l50t"/><path fill="url(#iXiPo5d)" class="cv5r0l50t"/><path class="ru23k_bum"/><path fill="url(#ilma11b)" class="in0xfwm-e"/><path fill="url(#ia4b6BH)" class="in0xfwm-e"/><g filter="url(#iJxt5ne)"><path fill="url(#ipEZRzb)" class="ig6_2yjak"/></g><path class="ugj18ybwx"/><path fill="url(#irc04fb)" class="r734yisuq"/><path fill="url(#i5qzgcb)" class="r734yisuq"/><path fill="url(#i1DKGse)" class="r734yisuq"/><path fill="url(#ifnKwNe)" class="r734yisuq"/><g filter="url(#iVJzXAc)"><path fill="url(#ihlARdc)" class="wwy5plbpo"/><path fill="url(#iswOmFb)" class="wwy5plbpo"/><path fill="url(#iwGvF6d)" class="wwy5plbpo"/><path fill="url(#iBXueZb)" class="wwy5plbpo"/><path fill="url(#ip52RWb)" class="wwy5plbpo"/><path fill="url(#iIhHT2e)" class="wwy5plbpo"/></g><g filter="url(#iKCKR3m)"><path class="rt_k9wbor"/><path fill="url(#iBPjgJe)" class="xa3zyvbne"/><path fill="url(#iFjgdic)" class="xa3zyvbne"/><path fill="url(#ibyIlhd)" class="xa3zyvbne"/><path fill="url(#icdnVie)" class="xa3zyvbne"/><path fill="url(#if2jucb)" class="xa3zyvbne"/><path fill="url(#igi8oPb)" class="xa3zyvbne"/><path fill="url(#iwHGyKe)" class="xa3zyvbne"/><path fill="url(#iZQDFOY)" class="xa3zyvbne"/></g><path fill="url(#ijLHReb)" class="xa3zyvbne"/><path fill="url(#inLtKmc)" class="xa3zyvbne"/><g filter="url(#isevl5d)"><path class="vq0s7abyd"/></g><g filter="url(#ixvdU0c)"><path class="mdy2dzrad"/></g><path fill="url(#i2L2eje)" class="ws-8jy8or"/><path fill="url(#ibjD9ye)" class="ws-8jy8or"/><path fill="url(#iRJIlyb)" class="ws-8jy8or"/><path fill="url(#idita0c)" class="p4vvbrjbk"/><path fill="url(#iaqzLHh)" class="p4vvbrjbk"/><path fill="url(#ijyCfke)" class="p4vvbrjbk"/><path class="ddans_79k"/><path fill="url(#i1gNbTd)" class="cd73asbyy"/><path fill="url(#i5NANxd)" class="cd73asbyy"/><path fill="url(#iCufqNd)" class="cd73asbyy"/><path fill="url(#inKDuPe)" class="cd73asbyy"/><path fill="url(#iIw17Dc)" class="cd73asbyy"/><path class="oo98hf_wm"/><path fill="url(#if1BaIb)" class="rp67l9b_i"/><path fill="url(#iuxM5Ge)" class="rp67l9b_i"/><path fill="url(#iyRsfib)" class="rp67l9b_i"/><path fill="url(#iBzYLQb)" class="rp67l9b_i"/><g filter="url(#iOZSnLb)"><path class="wrqvfubcf"/></g><g filter="url(#iZdPJku)"><path stroke="url(#i24R6Od)" class="y-tgsm-qx"/></g><g filter="url(#iEZ20Ve)"><ellipse fill="url(#isikxod)" class="z1_l4lb4v"/></g><g filter="url(#i9sXjpX)"><path fill="url(#isy5f2d)" class="xex_ohiza"/></g><g filter="url(#iN18Okc)"><path stroke="url(#iVU8kGd)" class="fjw-i7buc"/></g><g filter="url(#iRRX2Id)"><circle class="eg-4fdbmj"/></g><g filter="url(#i0ON3ke)"><circle class="e5g1jmbbj"/></g><g filter="url(#iHAp1Tc)"><circle class="acqqkyb9h"/></g><g filter="url(#im157Ke)"><circle class="urq7qibqh"/></g><defs><radialGradient id="iArPqEq" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 -.22656 .54727 2.3778 9.063 8.29)" gradientUnits="userSpaceOnUse"><stop class="qq7uk9bbo"/><stop offset="1" class="w-dy1ib1k"/></radialGradient><radialGradient id="iZupPAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 1.05662 -.96092 -.44762 16.492 4.363)" gradientUnits="userSpaceOnUse"><stop class="oqje67aig"/><stop offset="1" class="blz5zpbjp"/></radialGradient><radialGradient id="ipedU3b" cx="0" cy="0" r="1" gradientTransform="rotate(-124.786 9.782 -1.185)scale(2.49227 1.69871)" gradientUnits="userSpaceOnUse"><stop class="qq7uk9bbo"/><stop offset="1" class="w-dy1ib1k"/></radialGradient><radialGradient id="i68YR8c" cx="0" cy="0" r="1" gradientTransform="rotate(-87.732 10.282 -5.035)scale(.78968 .57767)" gradientUnits="userSpaceOnUse"><stop class="b0exujbup"/><stop offset="1" class="s5jy1ccdl"/></radialGradient><radialGradient id="irccdIb" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 1.03125 -.62584 .1043 15.297 2.469)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="kedpb8o8l"/><stop offset="1" class="e1qyoy_um"/></radialGradient><radialGradient id="iH4hoLb" cx="0" cy="0" r="1" gradientTransform="matrix(.7461 .11719 -.17523 1.11564 14.457 4.14)" gradientUnits="userSpaceOnUse"><stop class="qhh3jx79z"/><stop offset="1" class="efbyw6bej"/></radialGradient><radialGradient id="iEjMwPd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 1.05662 -.96092 -.44762 13.938 3.668)" gradientUnits="userSpaceOnUse"><stop class="oqje67aig"/><stop offset="1" class="blz5zpbjp"/></radialGradient><radialGradient id="iomeuBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92578 -1.20312 1.10822 -1.77387 13.828 3.781)" gradientUnits="userSpaceOnUse"><stop offset=".623" class="mhmjqxb3z"/><stop offset="1" class="gu7m1ebhp"/></radialGradient><radialGradient id="iUyF4bd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0703 .08594 -.07916 2.82811 12.29 3.805)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="mhmjqxb3z"/><stop offset=".944" class="gu7m1ebhp"/></radialGradient><radialGradient id="irVLSRS" cx="0" cy="0" r="1" gradientTransform="matrix(.57811 -1.78125 1.21409 .39404 12.641 4.969)" gradientUnits="userSpaceOnUse"><stop class="qq7uk9bbo"/><stop offset="1" class="w-dy1ib1k"/></radialGradient><radialGradient id="iimPrEP" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 1.05662 -.96092 -.44762 11.484 4.441)" gradientUnits="userSpaceOnUse"><stop class="oqje67aig"/><stop offset="1" class="blz5zpbjp"/></radialGradient><radialGradient id="iAH1cHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59376 -1.23437 1.137 -1.46803 11.25 4.61)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="mhmjqxb3z"/><stop offset="1" class="gu7m1ebhp"/></radialGradient><radialGradient id="iGzr9jc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.786 7.298 .163)scale(2.49227 1.69871)" gradientUnits="userSpaceOnUse"><stop class="qq7uk9bbo"/><stop offset="1" class="w-dy1ib1k"/></radialGradient><radialGradient id="iVgyjRb" cx="0" cy="0" r="1" gradientTransform="matrix(2.84375 -.96875 .89233 2.61942 9.953 4.844)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="mhmjqxb3z"/><stop offset=".944" class="gu7m1ebhp"/></radialGradient><radialGradient id="iTrS1ee" cx="0" cy="0" r="1" gradientTransform="matrix(-.13281 1.34375 -1.41117 -.13948 9.563 6.719)" gradientUnits="userSpaceOnUse"><stop class="oqje67aig"/><stop offset="1" class="blz5zpbjp"/></radialGradient><radialGradient id="iSJpcTb" cx="0" cy="0" r="1" gradientTransform="matrix(.97656 -.5 1.95452 3.81743 9.023 8.617)" gradientUnits="userSpaceOnUse"><stop class="qq7uk9bbo"/><stop offset="1" class="w-dy1ib1k"/></radialGradient><radialGradient id="iugkz2b" cx="0" cy="0" r="1" gradientTransform="rotate(167.683 4.509 4.067)scale(1.83121 3.15612)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="n2qsj_b5r"/><stop offset="1" class="h8r60ob3b"/></radialGradient><radialGradient id="iXad0Mv" cx="0" cy="0" r="1" gradientTransform="matrix(1.57812 -2.59375 1.86185 1.13281 8.875 7.484)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="mhmjqxb3z"/><stop offset=".944" class="gu7m1ebhp"/></radialGradient><radialGradient id="iITUWAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71114 -2.153 0 23.006 17.664)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="ixDZOnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .6369 -2.12667 0 23.139 14.441)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="ii1UA2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .62327 -2.07729 0 22.729 11.181)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="iNEkAzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71114 -2.153 0 9.014 17.664)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="i6DRWyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .6369 -2.12667 0 8.881 14.441)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="i6eMP3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .62327 -2.07729 0 9.291 11.181)" gradientUnits="userSpaceOnUse"><stop class="fo0w9bckk"/><stop offset="1" class="iblmb6lmo"/></radialGradient><radialGradient id="i2O1dvc" cx="0" cy="0" r="1" gradientTransform="matrix(4.61691 0 0 21.1935 9.258 15.842)" gradientUnits="userSpaceOnUse"><stop class="tlzhgbcbc"/><stop offset="1" class="g2rk6vbxn"/></radialGradient><radialGradient id="iuvYnAc" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 -.86719 .4128 .22686 11.297 11.149)" gradientUnits="userSpaceOnUse"><stop class="pl5xrrkcq"/><stop offset="1" class="ydp5o2ntb"/></radialGradient><radialGradient id="icNgNxu" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -.92969 .29213 .11783 10.844 14.336)" gradientUnits="userSpaceOnUse"><stop class="pl5xrrkcq"/><stop offset="1" class="ydp5o2ntb"/></radialGradient><radialGradient id="imBi8eb" cx="0" cy="0" r="1" gradientTransform="matrix(.82813 -1.46875 .4633 .26122 10.188 17.453)" gradientUnits="userSpaceOnUse"><stop class="pl5xrrkcq"/><stop offset="1" class="ydp5o2ntb"/></radialGradient><radialGradient id="iKejaKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.54687 .48952 -.89512 20.906 11.086)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="zh1nlgbpc"/><stop offset="1" class="sat7vq_qe"/></radialGradient><radialGradient id="iIj2VGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.52237 -.46977 .84673 -.94154 21.163 14.156)" gradientUnits="userSpaceOnUse"><stop class="no3z3lb2k"/><stop offset="1" class="qt9hg-bdx"/></radialGradient><radialGradient id="ipe3Rmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6279 -.6552 1.18097 -1.13176 21.573 16.928)" gradientUnits="userSpaceOnUse"><stop class="no3z3lb2k"/><stop offset="1" class="qt9hg-bdx"/></radialGradient><radialGradient id="iZlExRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.27598 11.6603 0 16.55 18.075)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="wiiay0bfp"/><stop offset="1" class="q6u6eoaaq"/></radialGradient><radialGradient id="iVTEErb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.2422 2.31743 -1.6617 -3.04183 23.25 26.672)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="u47772btr"/><stop offset=".999" class="osd1swb7s"/></radialGradient><radialGradient id="i7W9nWE" cx="0" cy="0" r="1" gradientTransform="rotate(51.582 -12.81 36.305)scale(1.15667 1.75063)" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></radialGradient><radialGradient id="iUPWJRb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 .75 -3.84231 1.28077 21.235 24.781)" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></radialGradient><radialGradient id="il17ANd" cx="0" cy="0" r="1" gradientTransform="rotate(-13.12 128.293 -72.32)scale(5.23132 1.38018)" gradientUnits="userSpaceOnUse"><stop class="z-tjfjbdm"/><stop offset="1" class="agtsf-b5r"/></radialGradient><radialGradient id="i7nt9we" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 0 0 2.17188 23.234 28.844)" gradientUnits="userSpaceOnUse"><stop class="jsxrvb28y"/><stop offset="1" class="j818h7gcy"/></radialGradient><radialGradient id="ilWikue" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.03125 .54688 0 23.828 22.328)" gradientUnits="userSpaceOnUse"><stop class="jsxrvb28y"/><stop offset="1" class="j818h7gcy"/></radialGradient><radialGradient id="isZxfAb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -1.10937 .23598 .1396 18.844 27.078)" gradientUnits="userSpaceOnUse"><stop class="jsxrvb28y"/><stop offset="1" class="j818h7gcy"/></radialGradient><radialGradient id="ifnKwNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26563 .8338 -.08091 -.12282 13.219 27.994)" gradientUnits="userSpaceOnUse"><stop class="oi3z-hbab"/><stop offset="1" class="n94_szb-u"/></radialGradient><radialGradient id="iwGvF6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .90625 -1.37162 -1.08783 8.406 23.781)" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></radialGradient><radialGradient id="iBXueZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 .75 -3.8423 -1.28077 10.766 24.781)" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></radialGradient><radialGradient id="ip52RWb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.351 8.054 12.903)scale(5.38718 1.18989)" gradientUnits="userSpaceOnUse"><stop class="z-tjfjbdm"/><stop offset="1" class="agtsf-b5r"/></radialGradient><radialGradient id="iBPjgJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8 -9.90625 0 16.01 16.29)" gradientUnits="userSpaceOnUse"><stop offset=".844" class="ptj79tb2h"/><stop offset="1" class="osyplojey"/></radialGradient><radialGradient id="iFjgdic" cx="0" cy="0" r="1" gradientTransform="matrix(3.09375 -2.59375 3.48252 4.15386 10.781 22.313)" gradientUnits="userSpaceOnUse"><stop class="osyplojey"/><stop offset="1" class="ptj79tb2h"/></radialGradient><radialGradient id="ibyIlhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.83496 8.02126 0 16.01 23.125)" gradientUnits="userSpaceOnUse"><stop class="m33-tfwbs"/><stop offset="1" class="w7x26mj9d"/></radialGradient><radialGradient id="icdnVie" cx="0" cy="0" r="1" gradientTransform="rotate(137.534 7.028 13.34)scale(2.49941 2.6837)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="m3blkusbz"/><stop offset="1" class="dxldutbeg"/></radialGradient><radialGradient id="if2jucb" cx="0" cy="0" r="1" gradientTransform="rotate(-145.185 13.465 9.01)scale(11.604 10.2219)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="e5ydb7i5j"/><stop offset="1" class="rvq55pbzc"/></radialGradient><radialGradient id="igi8oPb" cx="0" cy="0" r="1" gradientTransform="rotate(-42.312 37.767 -6.785)scale(9.42373 7.77728)" gradientUnits="userSpaceOnUse"><stop offset=".899" class="e5ydb7i5j"/><stop offset="1" class="rvq55pbzc"/></radialGradient><radialGradient id="iwHGyKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04687 1.40625 0 17.156 24.148)" gradientUnits="userSpaceOnUse"><stop class="z5c1tjb_c"/><stop offset="1" class="y_hip__5j"/></radialGradient><radialGradient id="iZQDFOY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.10156 1.50781 0 14.656 24.195)" gradientUnits="userSpaceOnUse"><stop class="z5c1tjb_c"/><stop offset="1" class="y_hip__5j"/></radialGradient><radialGradient id="ijLHReb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.6875 2.0049 1.91376 11.11 23.156)" gradientUnits="userSpaceOnUse"><stop class="k9s5w4mki"/><stop offset="1" class="ps2wl-bhq"/></radialGradient><radialGradient id="inLtKmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49121 -6.64062 0 15.828 16.29)" gradientUnits="userSpaceOnUse"><stop class="o6amhkbia"/><stop offset="1" class="j1i-pgh9k"/></radialGradient><radialGradient id="i2L2eje" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 4.293 14.79)scale(1.38773 1.23721)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ibjD9ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .48437 -.42613 -.46737 18.874 20.04)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="idita0c" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 1.803 13.516)scale(1.38773 1.23721)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iaqzLHh" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .48437 -.42613 -.46737 13.894 20.04)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i1gNbTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.05587 -.5 0 14.984 23.382)" gradientUnits="userSpaceOnUse"><stop class="nqvz8dble"/><stop offset="1" class="j8neuz_xd"/></radialGradient><radialGradient id="i5NANxd" cx="0" cy="0" r="1" gradientTransform="rotate(-116.053 15.631 8.45)scale(1.56531 1.17981)" gradientUnits="userSpaceOnUse"><stop class="y7qq9gb7i"/><stop offset="1" class="c5gym6_om"/></radialGradient><radialGradient id="iCufqNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17969 .4297 -.7052 -1.93606 14.906 24.477)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="a9m8fzd6e"/><stop offset="1" class="yq6py1n-a"/></radialGradient><radialGradient id="iIw17Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.35095 1.5547 -.49277 .11124 13.297 23.836)" gradientUnits="userSpaceOnUse"><stop class="nqvz8dble"/><stop offset="1" class="j8neuz_xd"/></radialGradient><radialGradient id="if1BaIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 2.05587 -.5 -.0608 17.563 23.382)" gradientUnits="userSpaceOnUse"><stop class="nqvz8dble"/><stop offset="1" class="j8neuz_xd"/></radialGradient><radialGradient id="iuxM5Ge" cx="0" cy="0" r="1" gradientTransform="matrix(.45929 -1.04687 .93944 .41215 16.884 26.203)" gradientUnits="userSpaceOnUse"><stop class="y7qq9gb7i"/><stop offset="1" class="c5gym6_om"/></radialGradient><radialGradient id="iyRsfib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73438 -.01562 .02564 -2.84641 17.875 24.578)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="a9m8fzd6e"/><stop offset="1" class="yq6py1n-a"/></radialGradient><radialGradient id="isikxod" cx="0" cy="0" r="1" gradientTransform="matrix(-3.69983 .37888 -.25046 -2.44574 19.5 7.871)" gradientUnits="userSpaceOnUse"><stop class="jmwci4b5n"/><stop offset="1" class="bpwjbpb5x"/></radialGradient><linearGradient id="iAMWAAc" x1="21.23" x2="26.141" y1="17.568" y2="17.844" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="i4nLYcb" x1="21.385" x2="26.232" y1="14.355" y2="14.656" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="iJiC12b" x1="21.016" x2="25.75" y1="11.097" y2="11.391" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="iOff8we" x1="10.79" x2="5.879" y1="17.568" y2="17.844" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="iDgUvUb" x1="8.547" x2="8.625" y1="13.632" y2="15.203" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="ifgWgFe" x1="8.969" x2="8.781" y1="10.063" y2="12.531" gradientUnits="userSpaceOnUse"><stop class="mfsi_h8qy"/><stop offset="1" class="qf4am1ptm"/></linearGradient><linearGradient id="i2EJ1le" x1="16.013" x2="16.013" y1="5.132" y2="15.842" gradientUnits="userSpaceOnUse"><stop class="qlfep9b6j"/><stop offset="1" class="xpg7qbdiy"/><stop offset="1" class="gxknhy1rj"/></linearGradient><linearGradient id="ibB1vWn" x1="18.714" x2="18.714" y1="7.125" y2="17" gradientUnits="userSpaceOnUse"><stop class="uh54x5b5n"/><stop offset="1" class="m36fnj-vy"/></linearGradient><linearGradient id="i4p2f6b" x1="22.675" x2="22.675" y1="21" y2="22.109" gradientUnits="userSpaceOnUse"><stop class="ilal8ookm"/><stop offset="1" class="ds9kaacao"/></linearGradient><linearGradient id="is5gZGc" x1="22.675" x2="22.675" y1="19.781" y2="20.344" gradientUnits="userSpaceOnUse"><stop class="y1568vb_y"/><stop offset="1" class="wrvdbgwqw"/></linearGradient><linearGradient id="iTjdsCc" x1="21.499" x2="21.499" y1="28.125" y2="28.563" gradientUnits="userSpaceOnUse"><stop class="jcl__jbdu"/><stop offset="1" class="hpbc9wd1o"/></linearGradient><linearGradient id="i9pBh9c" x1="21.499" x2="21.499" y1="28.989" y2="29.984" gradientUnits="userSpaceOnUse"><stop class="kfigv3z3x"/><stop offset="1" class="klo6e99mz"/></linearGradient><linearGradient id="i1gIqkZ" x1="22.896" x2="23.991" y1="29.203" y2="29.717" gradientUnits="userSpaceOnUse"><stop class="kfigv3z3x"/><stop offset="1" class="klo6e99mz"/></linearGradient><linearGradient id="i96xMod" x1="23.583" x2="29.266" y1="21.016" y2="21.016" gradientUnits="userSpaceOnUse"><stop class="ku-kaf23v"/><stop offset="1" class="k0-fi1bxf"/></linearGradient><linearGradient id="iL8eJ3b" x1="23.991" x2="23.99" y1="20" y2="27.938" gradientUnits="userSpaceOnUse"><stop class="hvq-x5bti"/><stop offset="1" class="yfzvbl9nd"/></linearGradient><linearGradient id="inQW4Jc" x1="23.99" x2="23.99" y1="28.5" y2="29.984" gradientUnits="userSpaceOnUse"><stop class="m1qjdj8nq"/><stop offset="1" class="ekbhxrbuh"/></linearGradient><linearGradient id="iWn2Xid" x1="29.407" x2="27.814" y1="25.594" y2="25.594" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></linearGradient><linearGradient id="iXiPo5d" x1="24.313" x2="24.953" y1="20.172" y2="20.906" gradientUnits="userSpaceOnUse"><stop offset=".274" class="tq-h0jb8a"/><stop offset="1" class="b904eobbb"/></linearGradient><linearGradient id="ilma11b" x1="9.335" x2="9.335" y1="21" y2="22.109" gradientUnits="userSpaceOnUse"><stop class="ilal8ookm"/><stop offset="1" class="ds9kaacao"/></linearGradient><linearGradient id="ia4b6BH" x1="9.335" x2="9.335" y1="19.781" y2="20.344" gradientUnits="userSpaceOnUse"><stop class="y1568vb_y"/><stop offset="1" class="wrvdbgwqw"/></linearGradient><linearGradient id="ipEZRzb" x1="7.597" x2="11.016" y1="21" y2="20.953" gradientUnits="userSpaceOnUse"><stop class="v7o_v9p1n"/><stop offset="1" class="qrrby9fkk"/></linearGradient><linearGradient id="irc04fb" x1="10.506" x2="10.506" y1="28.125" y2="28.563" gradientUnits="userSpaceOnUse"><stop class="jcl__jbdu"/><stop offset="1" class="hpbc9wd1o"/></linearGradient><linearGradient id="i5qzgcb" x1="10.506" x2="10.506" y1="28.989" y2="29.984" gradientUnits="userSpaceOnUse"><stop class="kfigv3z3x"/><stop offset="1" class="klo6e99mz"/></linearGradient><linearGradient id="i1DKGse" x1="11.906" x2="13.002" y1="29.203" y2="29.719" gradientUnits="userSpaceOnUse"><stop class="kfigv3z3x"/><stop offset="1" class="klo6e99mz"/></linearGradient><linearGradient id="ihlARdc" x1="8.01" x2="8.01" y1="20" y2="29.156" gradientUnits="userSpaceOnUse"><stop class="hvq-x5bti"/><stop offset="1" class="yfzvbl9nd"/></linearGradient><linearGradient id="iswOmFb" x1="8.011" x2="8.011" y1="28.5" y2="29.984" gradientUnits="userSpaceOnUse"><stop class="m1qjdj8nq"/><stop offset="1" class="ekbhxrbuh"/></linearGradient><linearGradient id="iIhHT2e" x1="2.594" x2="4.188" y1="25.594" y2="25.594" gradientUnits="userSpaceOnUse"><stop class="woeyythqy"/><stop offset="1" class="v309vxh6z"/></linearGradient><linearGradient id="iRJIlyb" x1="18.303" x2="17.616" y1="19.505" y2="19.067" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ijyCfke" x1="13.323" x2="12.636" y1="19.505" y2="19.067" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="inKDuPe" x1="15.398" x2="15.633" y1="24.683" y2="24.683" gradientUnits="userSpaceOnUse"><stop class="a9m8fzd6e"/><stop offset="1" class="yq6py1n-a"/></linearGradient><linearGradient id="iBzYLQb" x1="17.813" x2="18.143" y1="24.859" y2="24.922" gradientUnits="userSpaceOnUse"><stop class="a9m8fzd6e"/><stop offset="1" class="yq6py1n-a"/></linearGradient><linearGradient id="i24R6Od" x1="8.125" x2="13.75" y1="21.688" y2="27.281" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></linearGradient><linearGradient id="isy5f2d" x1="12.484" x2="10.484" y1="26.313" y2="25.336" gradientUnits="userSpaceOnUse"><stop class="i6i839zlx"/><stop offset="1" class="j-pk_xb5x"/></linearGradient><linearGradient id="iVU8kGd" x1="27.391" x2="27.391" y1="21.188" y2="29.125" gradientUnits="userSpaceOnUse"><stop class="zf1cixbgq"/><stop offset="1" class="m6q0hhb_m"/></linearGradient><filter id="iSgbKmN" width="6.359" height="2.864" x="19.801" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="iYNBX7d" width="6.159" height="2.664" x="19.926" y="16.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="ic3ll5d" width="6.297" height="2.696" x="19.965" y="13.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="i0awTyx" width="6.097" height="2.496" x="20.09" y="13.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="iXwb0mb" width="6.18" height="2.665" x="19.614" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="i8hVF1d" width="5.98" height="2.465" x="19.739" y="9.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="i8OxBGc" width="6.359" height="2.864" x="5.859" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="i1Nc0Cb" width="6.159" height="2.664" x="5.934" y="16.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="iIFk8rT" width="6.297" height="2.696" x="5.758" y="13.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="iGF6Sde" width="6.097" height="2.496" x="5.833" y="13.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="ijVFUsc" width="6.18" height="2.665" x="6.226" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.458824 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="im32yAY" width="5.98" height="2.465" x="6.301" y="9.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".2"/></filter><filter id="iA8KgGb" width="4.717" height="4.171" x="11.75" y="4.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".375"/></filter><filter id="ij6EVUc" width="8.803" height="16.938" x="14.313" y="4.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation="1.25"/></filter><filter id="iJsMndc" width="4.306" height="1.399" x="21.43" y="20.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".25"/></filter><filter id="iJxt5ne" width="4.306" height="1.399" x="6.042" y="20.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".25"/></filter><filter id="iVJzXAc" width="10.132" height="9.984" x="3.02" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.635294 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="iKCKR3m" width="12.424" height="8" x="9.848" y="16.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.580392 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6701"/></filter><filter id="isevl5d" width="2.789" height="2.789" x="16.953" y="19.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".25"/></filter><filter id="ixvdU0c" width="2.914" height="2.914" x="11.899" y="18.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".25"/></filter><filter id="iOZSnLb" width="2.188" height="4.094" x="6.953" y="26.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".375"/></filter><filter id="iZdPJku" width="7.316" height="7.113" x="5.569" y="19.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".5"/></filter><filter id="iEZ20Ve" width="5.7" height="3.492" x="14.8" y="6.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".5"/></filter><filter id="i9sXjpX" width="2.048" height="1.572" x="10.636" y="25.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".1"/></filter><filter id="iN18Okc" width="3.406" height="8.813" x="25.688" y="19.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".5"/></filter><filter id="iRRX2Id" width="2.341" height="2.341" x="8.744" y="5.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".3"/></filter><filter id="i0ON3ke" width="2.442" height="2.442" x="10.517" y="3.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".3"/></filter><filter id="iHAp1Tc" width="2.481" height="2.481" x="12.798" y="2.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".3"/></filter><filter id="im157Ke" width="2.36" height="2.36" x="15.41" y="2.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6701" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scorpion" /></template>
<style>
.a0o5ylb4a {
  d: path("M6.358 15.078a3.113 3.113 0 0 1 5.047-.284");
}

.a9m8fzd6e {
  stop-color: var(--svg-color--4b282a, #4B282A);
  stop-opacity: 0;
}

.aaxcev0jp {
  fill: var(--svg-color--603b42, #603B42);
  d: path("M23.49 27.994h-4.23c-.15 0-.27.14-.25.29c.14.96.97 1.7 1.97 1.7h3.01z");
}

.acqqkyb9h {
  cx: 14.039px;
  cy: 3.332px;
  r: 0.641px;
  fill: var(--svg-color--795f59, #795F59);
}

.agtsf-b5r {
  stop-color: var(--svg-color--76396b, #76396B);
  stop-opacity: 0;
}

.ancjbcimi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M25.662 15.078a3.113 3.113 0 0 0-5.046-.284");
}

.axifqjb6q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M25.56 18.375c-.64-1.169-2.757-2.711-5.109-.469");
}

.b0exujbup {
  stop-color: var(--svg-color--615453, #615453);
}

.b904eobbb {
  stop-color: var(--svg-color--4c2d2a, #4C2D2A);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bk6f83bgf {
  fill: var(--svg-color--654038, #654038);
  d: path("M27.5 22h-9.65v-2h8.7z");
}

.blz5zpbjp {
  stop-color: var(--svg-color--492f2a, #492F2A);
}

.bpwjbpb5x {
  stop-color: var(--svg-color--a47f77, #A47F77);
  stop-opacity: 0;
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c5gym6_om {
  stop-color: var(--svg-color--642f5f, #642F5F);
  stop-opacity: 0;
}

.c6lfh3b6m {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M6.358 15.078a3.113 3.113 0 0 1 5.047-.284");
}

.cd73asbyy {
  d: path("M14.623 23.383a1.04 1.04 0 0 0-.968.547c-.037.24.076 1.118.308 1.46c.27.397.608.532.823.576a.37.37 0 0 0 .275-.053c.361-.235.508-.65.508-.917v-1.105c-.086-.16-.396-.483-.946-.508");
}

.cg57ekzwo {
  d: path("M25.194 11.805c-.641-1.156-2.977-2.375-4.93-.258");
}

.chvrrkbvx {
  d: path("M10.867 6.621c0 .852-1.015 1.996-1.594 1.996c-.468 0-1.28-1.144-1.28-1.996s.643-1.523 1.444-1.523c.802 0 1.43.67 1.43 1.523");
}

.ck3k_wfle {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.46 18.375c.64-1.169 2.757-2.711 5.109-.469");
}

.cv5r0l50t {
  d: path("M26.731 20a2.25 2.25 0 0 1 2.25 2.25v4.314a3.43 3.43 0 0 1-1 2.417a3.4 3.4 0 0 1-2.41 1.003h-1.89a.5.5 0 0 1-.5-.501v-2.137c0-.2-.17-.371-.37-.371h-3.56c-.16 0-.27-.14-.25-.291c.11-.722.62-1.334 1.34-1.565l3.2-1.013c.26-.09.44-.331.44-.602V22a2 2 0 0 1 2-2z");
}

.ddans_79k {
  fill: var(--svg-color--62393d, #62393D);
  d: path("M14.623 23.383a1.04 1.04 0 0 0-.968.547c-.037.24.076 1.118.308 1.46c.27.397.608.532.823.576a.37.37 0 0 0 .275-.053c.361-.235.508-.65.508-.917v-1.105c-.086-.16-.396-.483-.946-.508");
}

.did7jilbi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.826 11.805c.641-1.156 2.977-2.375 4.93-.258");
}

.djts3zb8u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
}

.do_6cwmjy {
  d: path("M25.662 15.078a3.113 3.113 0 0 0-5.046-.284");
}

.ds9kaacao {
  stop-color: var(--svg-color--873a80, #873A80);
}

.dxldutbeg {
  stop-color: var(--svg-color--a57f76, #A57F76);
  stop-opacity: 0;
}

.e1qyoy_um {
  stop-color: var(--svg-color--685651, #685651);
  stop-opacity: 0;
}

.e5g1jmbbj {
  cx: 11.738px;
  cy: 4.383px;
  r: 0.621px;
  fill: var(--svg-color--705852, #705852);
}

.e5ydb7i5j {
  stop-color: var(--svg-color--98817b, #98817B);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ec9dzrsdg {
  d: path("M16.813 8.273v9.477l3.803 1.313l-1.518-10.947a1.148 1.148 0 0 0-2.285.157");
}

.efbyw6bej {
  stop-color: var(--svg-color--4f3028, #4F3028);
  stop-opacity: 0;
}

.eg-4fdbmj {
  cx: 9.914px;
  cy: 6.258px;
  r: 0.57px;
  fill: var(--svg-color--6f5853, #6F5853);
}

.ekbhxrbuh {
  stop-color: var(--svg-color--844579, #844579);
}

.fjw-i7buc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.938 21.188c.302 0 .906.193.906.968V27.5");
}

.flzpcw40p {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M25.56 18.375c-.64-1.169-2.757-2.711-5.109-.469");
}

.fo0w9bckk {
  stop-color: var(--svg-color--512d4f, #512D4F);
}

.ft5dv1b6b {
  fill: none;
}

.g2rk6vbxn {
  stop-color: var(--svg-color--908583, #908583);
  stop-opacity: 0;
}

.gu7m1ebhp {
  stop-color: var(--svg-color--837774, #837774);
}

.gxknhy1rj {
  stop-color: var(--svg-color--563530, #563530);
}

.h61yhotba {
  d: path("M6.826 11.805c.641-1.156 2.977-2.375 4.93-.258");
}

.h8r60ob3b {
  stop-color: var(--svg-color--6f5d60, #6F5D60);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hpbc9wd1o {
  stop-color: var(--svg-color--512928, #512928);
  stop-opacity: 0;
}

.hvq-x5bti {
  stop-color: var(--svg-color--5e3a36, #5E3A36);
}

.i6i839zlx {
  stop-color: var(--svg-color--836463, #836463);
}

.iblmb6lmo {
  stop-color: var(--svg-color--512d4f, #512D4F);
  stop-opacity: 0;
}

.ig6_2yjak {
  d: path("M6.542 20.655h3.306v.399H6.542z");
}

.ilal8ookm {
  stop-color: var(--svg-color--693765, #693765);
  stop-opacity: 0;
}

.in0xfwm-e {
  d: path("M4.51 22h9.65v-2h-8.7z");
}

.itozaqcjq {
  d: path("M23.49 27.994h-4.23c-.15 0-.27.14-.25.29c.14.96.97 1.7 1.97 1.7h3.01z");
}

.j-pk_xb5x {
  stop-color: var(--svg-color--836463, #836463);
  stop-opacity: 0;
}

.j1i-pgh9k {
  stop-color: var(--svg-color--83574e, #83574E);
  stop-opacity: 0;
}

.j818h7gcy {
  stop-color: var(--svg-color--977c7c, #977C7C);
  stop-opacity: 0;
}

.j8neuz_xd {
  stop-color: var(--svg-color--816261, #816261);
  stop-opacity: 0;
}

.jcl__jbdu {
  stop-color: var(--svg-color--512928, #512928);
}

.jla0qacrg {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M6.826 11.805c.641-1.156 2.977-2.375 4.93-.258");
}

.jmwci4b5n {
  stop-color: var(--svg-color--a47f77, #A47F77);
}

.jsxrvb28y {
  stop-color: var(--svg-color--977c7c, #977C7C);
}

.k0-fi1bxf {
  stop-color: var(--svg-color--6c4b45, #6C4B45);
  stop-opacity: 0;
}

.k9s5w4mki {
  stop-color: var(--svg-color--4a202a, #4A202A);
}

.kedpb8o8l {
  stop-color: var(--svg-color--685651, #685651);
}

.kfigv3z3x {
  stop-color: var(--svg-color--6c3464, #6C3464);
  stop-opacity: 0;
}

.klo6e99mz {
  stop-color: var(--svg-color--6c3464, #6C3464);
}

.ku-kaf23v {
  stop-color: var(--svg-color--7e554e, #7E554E);
}

.m17uq_e5y {
  d: path("M6.46 18.375c.64-1.169 2.757-2.711 5.109-.469");
}

.m1qjdj8nq {
  stop-color: var(--svg-color--844579, #844579);
  stop-opacity: 0;
}

.m33-tfwbs {
  stop-color: var(--svg-color--71325b, #71325B);
}

.m36fnj-vy {
  stop-color: var(--svg-color--8b6f6a, #8B6F6A);
}

.m3blkusbz {
  stop-color: var(--svg-color--a57f76, #A57F76);
}

.m6q0hhb_m {
  stop-color: var(--svg-color--8f7370, #8F7370);
  stop-opacity: 0;
}

.mdy2dzrad {
  fill: var(--svg-color--5f333b, #5F333B);
  d: path("M13.356 21.376a.957.957 0 1 0 0-1.914a.957.957 0 0 0 0 1.914");
}

.mfsi_h8qy {
  stop-color: var(--svg-color--5b403e, #5B403E);
}

.mhmjqxb3z {
  stop-color: var(--svg-color--837774, #837774);
  stop-opacity: 0;
}

.n2qsj_b5r {
  stop-color: var(--svg-color--6f5d60, #6F5D60);
  stop-opacity: 0;
}

.n94_szb-u {
  stop-color: var(--svg-color--77605e, #77605E);
  stop-opacity: 0;
}

.no3z3lb2k {
  stop-color: var(--svg-color--572c21, #572C21);
}

.nqvz8dble {
  stop-color: var(--svg-color--816261, #816261);
}

.nzb4st3-r {
  d: path("m21.93 19.462l-11.84-.01l1.691-10.578c.235-2.438 2.067-3.742 4.229-3.742c2.412 0 3.928 1.398 4.24 3.92z");
}

.o6amhkbia {
  stop-color: var(--svg-color--83574e, #83574E);
}

.oi3z-hbab {
  stop-color: var(--svg-color--77605e, #77605E);
}

.olam3_b5n {
  d: path("M21.93 20.616h3.306v.399H21.93z");
}

.oo98hf_wm {
  fill: var(--svg-color--62393d, #62393D);
  d: path("M17.167 23.383c.55-.025.875.354.97.547c.036.24-.077 1.118-.31 1.46c-.269.397-.607.532-.822.576a.37.37 0 0 1-.275-.053a1.16 1.16 0 0 1-.508-.917v-1.105c.086-.16.395-.483.945-.508");
}

.oporj11af {
  d: path("M25.56 18.375c-.64-1.169-2.757-2.711-5.109-.469");
}

.oqje67aig {
  stop-color: var(--svg-color--5e4037, #5E4037);
}

.osd1swb7s {
  stop-color: var(--svg-color--847576, #847576);
}

.osyplojey {
  stop-color: var(--svg-color--603537, #603537);
}

.owewqybdc {
  d: path("M27.5 22h-9.65v-2h8.7z");
}

.p0s-2mbfp {
  d: path("M14.68 5.163a.395.395 0 0 0-.502-.137a1.54 1.54 0 0 1-1.383.041a.376.376 0 0 0-.467.147c-.267.46-.765.77-1.336.77a.187.187 0 0 0-.176.226q.051.196.051.411c0 .852-1.015 1.996-1.594 1.996c-.468 0-1.28-1.144-1.28-1.996s.643-1.523 1.444-1.523a.108.108 0 0 0 .1-.141a1.543 1.543 0 0 1 2.105-1.915a.376.376 0 0 0 .468-.147a1.542 1.542 0 0 1 2.655-.026a.395.395 0 0 0 .502.136a1.543 1.543 0 1 1-.587 2.158");
}

.p4vvbrjbk {
  d: path("M13.52 21.29a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.pl5xrrkcq {
  stop-color: var(--svg-color--43241d, #43241D);
}

.ps2wl-bhq {
  stop-color: var(--svg-color--4a202a, #4A202A);
  stop-opacity: 0;
}

.ptj79tb2h {
  stop-color: var(--svg-color--603537, #603537);
  stop-opacity: 0;
}

.q6u6eoaaq {
  stop-color: var(--svg-color--53352f, #53352F);
  stop-opacity: 0;
}

.qf4am1ptm {
  stop-color: var(--svg-color--77615c, #77615C);
}

.qhh3jx79z {
  stop-color: var(--svg-color--4f3028, #4F3028);
}

.qlfep9b6j {
  stop-color: var(--svg-color--895c4e, #895C4E);
}

.qq7uk9bbo {
  stop-color: var(--svg-color--4f2e40, #4F2E40);
}

.qrrby9fkk {
  stop-color: var(--svg-color--63443f, #63443F);
  stop-opacity: 0;
}

.qt9hg-bdx {
  stop-color: var(--svg-color--572c21, #572C21);
  stop-opacity: 0;
}

.qyi_zq9xe {
  fill: var(--svg-color--623e34, #623E34);
  d: path("M14.865 6.02a.67.67 0 0 0-.341.141a1.4 1.4 0 0 1-.397.258a.63.63 0 0 0-.25.241a1.2 1.2 0 0 1-.35.327c-.032.02-.025.078 0 .105l.016.02c.083.13-.167.534-.373.665c-.166.106-.566.115-.648-.014c-.083-.13.08-.378.366-.56c.019-.011.014-.044-.007-.055a.13.13 0 0 1-.053-.047c-.082-.13.096-.391.4-.584q.098-.062.195-.105a.63.63 0 0 0 .25-.24c.07-.11.194-.227.351-.327c.152-.097.307-.158.434-.179a.67.67 0 0 0 .34-.14q.088-.08.201-.153c.303-.193.616-.244.698-.114c.083.13-.096.39-.399.584a1.2 1.2 0 0 1-.433.178");
}

.r-44o0dxo {
  cx: 13.445px;
  cy: 3.668px;
  r: 1.543px;
}

.r734yisuq {
  d: path("M8.52 27.994h4.23c.15 0 .27.14.25.29c-.15.96-.98 1.7-1.98 1.7H8.01z");
}

.rp67l9b_i {
  d: path("M17.167 23.383c.55-.025.875.354.97.547c.036.24-.077 1.118-.31 1.46c-.269.397-.607.532-.822.576a.37.37 0 0 1-.275-.053a1.16 1.16 0 0 1-.508-.917v-1.105c.086-.16.395-.483.945-.508");
}

.rt_k9wbor {
  fill: var(--svg-color--7e4c41, #7E4C41);
  d: path("M18.05 24.29h-4.08c-2.277 0-4.122-1.79-4.122-4s1.845-4 4.122-4h4.08c2.277 0 4.122 1.79 4.122 4s-1.845 4-4.122 4");
}

.ru23k_bum {
  fill: var(--svg-color--4d322e, #4D322E);
  d: path("M4.51 22h9.65v-2h-8.7z");
}

.rvq55pbzc {
  stop-color: var(--svg-color--98817b, #98817B);
}

.ry3kdy46i {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M25.194 11.805c-.641-1.156-2.977-2.375-4.93-.258");
}

.s5jy1ccdl {
  stop-color: var(--svg-color--615453, #615453);
  stop-opacity: 0;
}

.s68m5bbkm {
  fill: var(--svg-color--492f2a, #492F2A);
  d: path("M14.68 5.163a.395.395 0 0 0-.502-.137a1.54 1.54 0 0 1-1.383.041a.376.376 0 0 0-.467.147c-.267.46-.765.77-1.336.77a.187.187 0 0 0-.176.226q.051.196.051.411c0 .852-1.015 1.996-1.594 1.996c-.468 0-1.28-1.144-1.28-1.996s.643-1.523 1.444-1.523a.108.108 0 0 0 .1-.141a1.543 1.543 0 0 1 2.105-1.915a.376.376 0 0 0 .468-.147a1.542 1.542 0 0 1 2.655-.026a.395.395 0 0 0 .502.136a1.543 1.543 0 1 1-.587 2.158");
}

.sat7vq_qe {
  stop-color: var(--svg-color--714a3f, #714A3F);
  stop-opacity: 0;
}

.sm3quyfdj {
  cx: 10.992px;
  cy: 4.441px;
  r: 1.543px;
}

.tlzhgbcbc {
  stop-color: var(--svg-color--908583, #908583);
}

.tq-h0jb8a {
  stop-color: var(--svg-color--4c2d2a, #4C2D2A);
}

.u47772btr {
  stop-color: var(--svg-color--847576, #847576);
  stop-opacity: 0;
}

.ugj18ybwx {
  fill: var(--svg-color--603b42, #603B42);
  d: path("M8.52 27.994h4.23c.15 0 .27.14.25.29c-.15.96-.98 1.7-1.98 1.7H8.01z");
}

.uh54x5b5n {
  stop-color: var(--svg-color--a27d75, #A27D75);
}

.unwt0ub1f {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M25.662 15.078a3.113 3.113 0 0 0-5.046-.284");
}

.urq7qibqh {
  cx: 16.59px;
  cy: 3.912px;
  r: 0.58px;
  fill: var(--svg-color--795f59, #795F59);
}

.uz595pb0z {
  cx: 16px;
  cy: 4.363px;
  r: 1.543px;
}

.v309vxh6z {
  stop-color: var(--svg-color--5b322d, #5B322D);
  stop-opacity: 0;
}

.v7o_v9p1n {
  stop-color: var(--svg-color--63443f, #63443F);
}

.vq0s7abyd {
  fill: var(--svg-color--643243, #643243);
  d: path("M18.348 21.376a.895.895 0 1 0 0-1.79a.895.895 0 0 0 0 1.79");
}

.w-dy1ib1k {
  stop-color: var(--svg-color--4f2e40, #4F2E40);
  stop-opacity: 0;
}

.w7x26mj9d {
  stop-color: var(--svg-color--642f52, #642F52);
  stop-opacity: 0;
}

.wiiay0bfp {
  stop-color: var(--svg-color--53352f, #53352F);
}

.woeyythqy {
  stop-color: var(--svg-color--5b322d, #5B322D);
}

.wrqvfubcf {
  fill: var(--svg-color--9a6d6c, #9A6D6C);
  d: path("m7.703 26.828l.688.25v2.344l-.688-.25z");
}

.wrvdbgwqw {
  stop-color: var(--svg-color--665856, #665856);
  stop-opacity: 0;
}

.ws-8jy8or {
  d: path("M18.5 21.29a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.wwy5plbpo {
  d: path("M5.27 20a2.25 2.25 0 0 0-2.25 2.25v4.314c0 .902.36 1.775 1 2.417a3.4 3.4 0 0 0 2.41 1.003h1.89a.5.5 0 0 0 .5-.501v-2.137c0-.2.17-.371.37-.371h3.56c.16 0 .27-.14.25-.291a1.95 1.95 0 0 0-1.34-1.565l-3.2-1.013a.645.645 0 0 1-.44-.602V22a2 2 0 0 0-2-2z");
}

.xa3zyvbne {
  d: path("M18.05 24.29h-4.08c-2.277 0-4.122-1.79-4.122-4s1.845-4 4.122-4h4.08c2.277 0 4.122 1.79 4.122 4s-1.845 4-4.122 4");
}

.xex_ohiza {
  d: path("M11.945 25.758c.346.214.49.58.54.75c-.4-.525-1.141-.75-1.65-.844l.102-.328c.123.029.696.228 1.008.422");
}

.xpg7qbdiy {
  stop-color: var(--svg-color--63332a, #63332A);
}

.y_hip__5j {
  stop-color: var(--svg-color--5c2b3b, #5C2B3B);
  stop-opacity: 0;
}

.y-tgsm-qx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M6.719 21.016c.172.057.515.328.515.953v1.652a1 1 0 0 0 .687.95l3.813 1.257");
}

.y1568vb_y {
  stop-color: var(--svg-color--665856, #665856);
}

.y483f1bui {
  stroke: var(--svg-color--4b292c, #4B292C);
  d: path("M6.46 18.375c.64-1.169 2.757-2.711 5.109-.469");
}

.y7qq9gb7i {
  stop-color: var(--svg-color--642f5f, #642F5F);
}

.ydp5o2ntb {
  stop-color: var(--svg-color--51312a, #51312A);
  stop-opacity: 0;
}

.yfzvbl9nd {
  stop-color: var(--svg-color--844e59, #844E59);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yq6py1n-a {
  stop-color: var(--svg-color--4b282a, #4B282A);
}

.z-tjfjbdm {
  stop-color: var(--svg-color--76396b, #76396B);
}

.z1_l4lb4v {
  cx: 17.65px;
  cy: 7.871px;
  rx: 1.85px;
  ry: 0.746px;
}

.z5c1tjb_c {
  stop-color: var(--svg-color--5c2b3b, #5C2B3B);
}

.zf1cixbgq {
  stop-color: var(--svg-color--8f7370, #8F7370);
}

.zh1nlgbpc {
  stop-color: var(--svg-color--543127, #543127);
}

.zlvwmnbye {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M25.194 11.805c-.641-1.156-2.977-2.375-4.93-.258");
}

.zpyr3xbsc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.358 15.078a3.113 3.113 0 0 1 5.047-.284");
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

</style>
