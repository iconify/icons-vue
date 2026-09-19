<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixvYEQe)"><path fill="url(#i8J3eXk)" class="w0lgbgbhh"/><path fill="url(#izYK5Hc)" class="w0lgbgbhh"/><path fill="url(#i3rodPc)" class="w0lgbgbhh"/></g><g filter="url(#i37Lpre)"><path fill="url(#iRujXJe)" class="h-5x17bxj"/></g><g filter="url(#iHlGYQc)"><path fill="url(#iiQlnXd)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#iKi3wtd)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#iVop8Eb)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#idtkawe)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#i9ZteZd)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#ipxFq7c)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#i9rP7md)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#igUjn2c)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#iFL0nbc)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#izSmO8e)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#i7HeYWd)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#iAIMn9b)" clip-rule="evenodd" class="s623_lb_x"/></g><path fill="url(#ictDNGc)" clip-rule="evenodd" class="s623_lb_x"/><path fill="url(#iJf1iUb)" class="shep8_bdh"/><path fill="url(#i2qypic)" class="shep8_bdh"/><path fill="url(#i8qGVjb)" class="shep8_bdh"/><path fill="url(#i3dimgb)" class="shep8_bdh"/><g filter="url(#igZuJZc)"><path class="lux6k2ifl"/></g><g filter="url(#is36L7b)"><path class="o7b0b7x3a"/></g><g filter="url(#i0Hl4Op)"><path fill="url(#ifH9sQd)" class="g-9p05b4a"/><path fill="url(#iqMD7gd)" class="g-9p05b4a"/><path fill="url(#isjlhEd)" class="g-9p05b4a"/></g><g filter="url(#i7KCKXb)"><path fill="url(#ilanV8c)" class="bxy9a_8wa"/><path fill="url(#iNWzONb)" class="bxy9a_8wa"/><path fill="url(#ieXxVFd)" class="bxy9a_8wa"/></g><g filter="url(#i7ron3c)"><path fill="url(#iIEcKAK)" class="dw40nqbxs"/><path fill="url(#iD56W9c)" class="dw40nqbxs"/><path fill="url(#iw9ww8d)" class="dw40nqbxs"/><path fill="url(#ik6Kw6b)" class="dw40nqbxs"/></g><path fill="url(#ifau3jC)" class="o2j9ljphc"/><path fill="url(#iZ9f8ke)" class="o2j9ljphc"/><g filter="url(#idWiuhb)"><path class="f9mex4b1c"/></g><g filter="url(#iayrmsc)"><path fill="url(#isd35Ge)" class="xv596dowm"/><path fill="url(#irrhvTu)" class="xv596dowm"/></g><g filter="url(#iEgqSmT)"><path fill="url(#iKh9DQb)" class="x0qjlw0mb"/><path fill="url(#iplo2Cc)" class="x0qjlw0mb"/></g><circle fill="url(#ioJN0Qd)" class="j-elh2uvv"/><circle fill="url(#ijowZ1b)" class="j-elh2uvv"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.426)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.426)" class="movji7bnz"/><circle fill="url(#ifbe9cT)" class="brgj7qtnd"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><path fill="url(#i2LQlsd)" class="ccrydivzf"/><g filter="url(#i6ApBIe)"><path class="hej-omb_k"/><path fill="url(#icPrSEd)" class="ntrmoswfw"/><path fill="url(#iNUb3Pc)" class="ntrmoswfw"/><path fill="url(#iRJHFee)" class="ntrmoswfw"/><path fill="url(#iptGC2c)" class="ntrmoswfw"/><path fill="url(#isTDdze)" class="ntrmoswfw"/></g><path fill="url(#ibyJhIe)" class="kcwstyspx"/><g filter="url(#iPeyAHd)"><path class="tpcvtjbvk"/><path fill="url(#iYuu2Rd)" class="o110mgbff"/><path fill="url(#iglME4c)" class="o110mgbff"/></g><g filter="url(#imgnKGc)"><path class="fo-imacds"/><path fill="url(#i84ZkMb)" class="f5jafwbws"/><path fill="url(#iBTolRe)" class="f5jafwbws"/><path fill="url(#iqD660c)" class="f5jafwbws"/><path fill="url(#iVpU4dr)" class="f5jafwbws"/><path fill="url(#iTMsRuF)" class="f5jafwbws"/></g><g filter="url(#irTpgmd)"><path fill="url(#in15rgd)" clip-rule="evenodd" class="yjp69hbuv"/></g><g filter="url(#iog2Dxc)"><path class="nj7exebgj"/></g><g filter="url(#is6sQhe)"><path fill="url(#iJ6OHFc)" class="z_qiivm8v"/><path fill="url(#ilfRpxc)" class="z_qiivm8v"/></g><g filter="url(#i9iJrJd)"><path stroke="url(#ihsvHFe)" class="jtc6ijb6j"/></g><g filter="url(#itWiUob)"><path stroke="url(#izL61sC)" class="hbyh_lbnn"/></g><g filter="url(#iWnLOyb)"><path stroke="url(#iMFCApc)" class="wn7tf0b0a"/></g><g filter="url(#iU63JvN)"><path stroke="url(#iP0FelY)" class="s9dopkbsv"/></g><path fill="url(#imsufLj)" class="uois0-_io"/><path fill="url(#ifZ0Quc)" class="jbqj6h9zn"/><g filter="url(#iaW9dNo)"><path fill="url(#ijLUv3b)" class="tf_jinbsn"/></g><g filter="url(#iqb8FTc)"><path fill="url(#il0FJHb)" class="p1bwqsbsy"/><path fill="url(#iy3GODZ)" class="p1bwqsbsy"/></g><g filter="url(#iB4BYWw)"><path class="ukkpznbub"/><path fill="url(#iD9ZNlc)" class="pjsve8bpd"/></g><g filter="url(#i1gqqet)"><path class="nx_ul7bge"/><path fill="url(#ie6C1ub)" class="mgnzdeb8x"/></g><g filter="url(#i8oumhe)"><path fill="url(#iW0MrRd)" class="my40ihbtn"/><path fill="url(#ihiD7Dc)" class="my40ihbtn"/><path fill="url(#iNoLXlb)" class="my40ihbtn"/><path fill="url(#iHrv49b)" class="my40ihbtn"/><path fill="url(#iCmT0Fd)" class="my40ihbtn"/><path fill="url(#iAy1Frb)" class="my40ihbtn"/><path fill="url(#iUfVPeb)" class="my40ihbtn"/><path fill="url(#izplOSb)" class="my40ihbtn"/></g><path fill="url(#icSOqre)" class="my40ihbtn"/><path fill="url(#iaGP7Yc)" class="my40ihbtn"/><g filter="url(#iXRGNfD)"><path class="dl8i_cb8p"/></g><g filter="url(#irKM0Fb)"><path class="pulj51b3e"/><path fill="url(#i57xpZk)" class="ll2igknmu"/><path fill="url(#inajeXc)" class="ll2igknmu"/><path fill="url(#iPFZBzj)" class="ll2igknmu"/><path fill="url(#iiFY3jc)" class="ll2igknmu"/></g><g filter="url(#iZrAUac)"><path stroke="url(#iLfr4hd)" class="o_6gh_hdi"/></g><path class="kldnr3qau"/><g filter="url(#iP8SEEc)"><path class="nvtd19bkp"/></g><g filter="url(#iptDS0d)"><path class="ef5hhgevp"/></g><g filter="url(#icjZJdd)"><path class="gi1u-g02v"/></g><g filter="url(#iXwp5xc)"><path clip-rule="evenodd" class="nn1bribyc"/></g><path class="ff1dam-wq"/><path fill="url(#i6LWYoe)" class="ch88whaiq"/><path class="eygxffb5y"/><g filter="url(#iERaTrb)"><path class="xlj1v1b_n"/><path fill="url(#iMgIfce)" class="v1t30ybxu"/></g><g filter="url(#iZEqSFb)"><path fill="url(#iYn1y7c)" class="k9pkqhbzh"/></g><path class="czy-shbsj"/><path fill="url(#ixwV2Je)" class="i3d34pb2k"/><path class="epr7emgds"/><g filter="url(#iEbHBLj)"><path fill="url(#iiXiWjc)" class="n35wtib-j"/></g><g filter="url(#iTZPC0c)"><ellipse transform="rotate(-27.914 13.617 9.874)" class="cbnddobix"/><ellipse fill="url(#iWdzOMc)" transform="rotate(-27.914 13.617 9.874)" class="nw78dlb5d"/></g><g filter="url(#iO8Uw8F)"><path class="ujsezfbfk"/></g><g filter="url(#iJ6oyYN)"><path class="v7knejbmk"/></g><g filter="url(#iUyg0EM)"><path class="igts4bbee"/><path fill="url(#iqzHxzc)" class="l_bchub-s"/></g><g filter="url(#iadoLMc)"><path class="d_40zvxgb"/><path fill="url(#iTZ2DZb)" class="iw2-npbkp"/><path fill="url(#ifMHHCe)" class="iw2-npbkp"/></g><g filter="url(#iOT8Q1m)"><path stroke="url(#ij7jlte)" class="yvn7twbfp"/></g><g filter="url(#i1q4Wsd)"><path class="ghbh5kb8u"/></g><g filter="url(#iVwGcRA)"><path fill="url(#iyk9OVd)" class="qxplm-b5k"/></g><g filter="url(#itwC1yc)"><path fill="url(#iqUG07c)" clip-rule="evenodd" class="bzjertbri"/><path fill="url(#iA6Kg8Z)" clip-rule="evenodd" class="bzjertbri"/></g><defs><radialGradient id="izYK5Hc" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.837 7.029)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="i3rodPc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.648)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iKi3wtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.769 13.069)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iVop8Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.953 13.336)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="idtkawe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.947 8.168)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i9ZteZd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.383 7.655)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ipxFq7c" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.199 11.642)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i9rP7md" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.001 6.83)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="igUjn2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.58 9.716)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iFL0nbc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.68 7.982)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="izSmO8e" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.006 -3.8)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i7HeYWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.928 9.68)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iAIMn9b" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.798 7.13)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iJf1iUb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.15 15.742)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="i8qGVjb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.024)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i3dimgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.18)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iqMD7gd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.819)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="isjlhEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.636 14.638)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iNWzONb" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.322)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="ieXxVFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.883)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iIEcKAK" cx="0" cy="0" r="1" gradientTransform="matrix(-7.77323 -2.8082 3.94394 -10.91704 21.531 21.602)" gradientUnits="userSpaceOnUse"><stop class="pq2t7lb5q"/><stop offset=".981" class="e7f-98b7z"/></radialGradient><radialGradient id="iD56W9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.61879 -1.42821 0 16.729 16.65)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="uct9hwfmk"/><stop offset="1" class="dsb0iwt3f"/></radialGradient><radialGradient id="iw9ww8d" cx="0" cy="0" r="1" gradientTransform="rotate(166.048 7.44 8.88)scale(5.1842 1.5763)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="p1f9bl61w"/><stop offset="1" class="x3lhf8m8j"/></radialGradient><radialGradient id="ik6Kw6b" cx="0" cy="0" r="1" gradientTransform="rotate(-143.653 14.525 6.708)scale(.91393 .73652)" gradientUnits="userSpaceOnUse"><stop class="nwmok1m8m"/><stop offset="1" class="debc6xrbn"/></radialGradient><radialGradient id="ifau3jC" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.766 35.893)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="irrhvTu" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.187 4.92)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iplo2Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.32)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="ioJN0Qd" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.312 11.808)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="ijowZ1b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.436 14.603)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ifbe9cT" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.348 12.664)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="i2LQlsd" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.378 19.374)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="icPrSEd" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.3 20.229)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iNUb3Pc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 23.023)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iRJHFee" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.178 9.23)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iptGC2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.821)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="isTDdze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.309 24.601)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="ibyJhIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.82)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iYuu2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.727)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iglME4c" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.74)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="i84ZkMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.305)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iBTolRe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.992)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="in15rgd" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.302 16.642)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iJ6OHFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.867)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="ilfRpxc" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.254)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="il0FJHb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.11 11.006)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iy3GODZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.14 8.886)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iD9ZNlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.462 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="ie6C1ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.47 10.567)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iW0MrRd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.93 10.03)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ihiD7Dc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.72 7.46)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iNoLXlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.89 16.812)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iHrv49b" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.777 12.476)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iCmT0Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 15.808 10.42)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iAy1Frb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.369 6.75)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iUfVPeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.372 9.611)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="izplOSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.994 9.382)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="icSOqre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.166 11.099)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iaGP7Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.991 15.145)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="i57xpZk" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.854 11.825)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iiFY3jc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.615 12.037)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i6LWYoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.252 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMgIfce" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.024 10.054)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixwV2Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.888 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWdzOMc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.816 -1.6)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqzHxzc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.32 -4.186)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iTZ2DZb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.16 6.974)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ifMHHCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.28 3.013)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iA6Kg8Z" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.662 8.597)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="ixvYEQe" width="21.944" height="26.818" x="4.962" y="3.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="i37Lpre" width="12.631" height="14.916" x="9.484" y="8.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/><feGaussianBlur result="effect2_foregroundBlur_4002_3410" stdDeviation=".05"/></filter><filter id="iHlGYQc" width="15.268" height="15.768" x="8.561" y="1.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="igZuJZc" width="5.874" height="5.537" x="6.993" y="23.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".5"/></filter><filter id="is36L7b" width="4.979" height="4.054" x="18.51" y="24.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".5"/></filter><filter id="i0Hl4Op" width="2.973" height="2.006" x="21.47" y="23.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="i7KCKXb" width="3.281" height="2" x="20.468" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="i7ron3c" width="13.965" height="11.381" x="9.149" y="12.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.192157 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="idWiuhb" width="10.996" height="6.432" x="11.932" y="21.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".5"/></filter><filter id="iayrmsc" width="2.973" height="2.006" x="7.658" y="23.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iEgqSmT" width="3.266" height="2" x="8.366" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="i6ApBIe" width="6.218" height="6.789" x="8.343" y="20.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3410" result="effect2_innerShadow_4002_3410"/></filter><filter id="iPeyAHd" width="6.218" height="6.639" x="17.574" y="20.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3410" result="effect2_innerShadow_4002_3410"/></filter><filter id="imgnKGc" width="6.702" height="6.417" x="12.683" y="20.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="irTpgmd" width="6.703" height="6.517" x="12.633" y="20.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".15"/></filter><filter id="iog2Dxc" width="3.2" height="3.2" x="14.271" y="22.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".25"/></filter><filter id="is6sQhe" width="2.35" height="2.35" x="14.893" y="23.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="i9iJrJd" width="1.458" height="2.505" x="15.848" y="20.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="itWiUob" width="1.723" height="1.924" x="16.94" y="24.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="iWnLOyb" width="1.368" height="2.217" x="18.104" y="22.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="iU63JvN" width="3.55" height="1.942" x="15.171" y="17.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".25"/></filter><filter id="iaW9dNo" width="3.368" height="3.218" x="9.775" y="8.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iqb8FTc" width="3.218" height="3.468" x="19.288" y="8.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iB4BYWw" width="3.148" height="3.148" x="19.323" y="8.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".25"/></filter><filter id="i1gqqet" width="2.648" height="2.648" x="10.08" y="9.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="i8oumhe" width="10.191" height="11.127" x="10.975" y="5.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iXRGNfD" width="2.877" height="3.682" x="14.469" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".25"/></filter><filter id="irKM0Fb" width="2.377" height="3.182" x="14.882" y="9.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="iZrAUac" width="3.702" height="1.526" x="14.219" y="12.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".05"/></filter><filter id="iP8SEEc" width="3.001" height="1.286" x="17.012" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iptDS0d" width="3.001" height="1.286" x="12.127" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="icjZJdd" width="2.453" height="1.091" x="12.262" y="7.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iXwp5xc" width="2.453" height="1.091" x="17.679" y="7.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><filter id="iERaTrb" width=".787" height=".696" x="17.518" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".05"/></filter><filter id="iZEqSFb" width=".891" height=".913" x="18.358" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".1"/></filter><filter id="iEbHBLj" width=".986" height="1.04" x="13.915" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".1"/></filter><filter id="iTZPC0c" width=".913" height=".704" x="13.16" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".05"/></filter><filter id="iO8Uw8F" width="2.461" height="1.178" x="17.61" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".1"/></filter><filter id="iJ6oyYN" width="2.461" height="1.178" x="12.158" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".1"/></filter><filter id="iUyg0EM" width="4.412" height="4.713" x="9.616" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/><feGaussianBlur result="effect2_foregroundBlur_4002_3410" stdDeviation=".25"/></filter><filter id="iadoLMc" width="8.767" height="5.782" x="12.9" y="2.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/><feGaussianBlur result="effect2_foregroundBlur_4002_3410" stdDeviation=".125"/></filter><filter id="iOT8Q1m" width="1.145" height="2.31" x="12.879" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".1"/></filter><filter id="i1q4Wsd" width="6.427" height="3.372" x="15.488" y="4.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".375"/></filter><filter id="iVwGcRA" width="8.285" height="5.027" x="14.004" y="3.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3410" stdDeviation=".5"/></filter><filter id="itwC1yc" width="15.448" height="4.54" x="8.283" y="2.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3410"/></filter><linearGradient id="i8J3eXk" x1="26.906" x2="11.7" y1="11.523" y2="21.523" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iRujXJe" x1="20.7" x2="10.387" y1="17.43" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iiQlnXd" x1="20.763" x2="13.958" y1="3.615" y2="16.219" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ictDNGc" x1="18.05" x2="18.05" y1="17.159" y2="16.331" gradientUnits="userSpaceOnUse"><stop class="a805_ab0d"/><stop offset="1" class="hbd2-pbjl"/></linearGradient><linearGradient id="i2qypic" x1="14.887" x2="14.887" y1="30.899" y2="29.617" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="ifH9sQd" x1="23.649" x2="21.867" y1="25.821" y2="24.41" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ilanV8c" x1="22.95" x2="21.169" y1="27.405" y2="25.711" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iZ9f8ke" x1="12.653" x2="13.255" y1="29.289" y2="28.945" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="isd35Ge" x1="7.856" x2="9.361" y1="24.305" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iKh9DQb" x1="9.062" x2="10.843" y1="27.404" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iqD660c" x1="14.919" x2="16.7" y1="27.168" y2="22.899" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iVpU4dr" x1="13.356" x2="16.981" y1="22.93" y2="23.617" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iTMsRuF" x1="17.231" x2="16.325" y1="26.93" y2="25.18" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="ihsvHFe" x1="16.477" x2="16.477" y1="20.852" y2="22.859" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="izL61sC" x1="17.286" x2="18.153" y1="24.906" y2="26.109" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iMFCApc" x1="18.728" x2="18.728" y1="22.438" y2="24.055" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iP0FelY" x1="16.132" x2="20.117" y1="19.05" y2="17.878" gradientUnits="userSpaceOnUse"><stop class="m7an_cnhm"/><stop offset="1" class="b-1v_fhcy"/></linearGradient><linearGradient id="imsufLj" x1="8.885" x2="23.261" y1="15.377" y2="15.377" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ifZ0Quc" x1="8.885" x2="23.261" y1="15.347" y2="15.347" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ijLUv3b" x1="9.775" x2="12.735" y1="10.654" y2="10.654" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="inajeXc" x1="15.132" x2="16.07" y1="11.898" y2="11.898" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iPFZBzj" x1="16.07" x2="16.07" y1="12.697" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iLfr4hd" x1="15.006" x2="15.467" y1="14.107" y2="13.395" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iYn1y7c" x1="19.03" x2="18.716" y1="10.024" y2="10.217" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiXiWjc" x1="14.632" x2="14.318" y1="10.024" y2="10.217" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ij7jlte" x1="13.179" x2="13.724" y1="4.369" y2="5.642" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iyk9OVd" x1="20.633" x2="13.008" y1="7.017" y2="4.736" gradientUnits="userSpaceOnUse"><stop class="xkb10lt3q"/><stop offset="1" class="uu1nbqb1f"/></linearGradient><linearGradient id="iqUG07c" x1="20.481" x2="8.544" y1="3.68" y2="7.367" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a805_ab0d {
  stop-color: var(--svg-color--483d53, #483D53);
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b-1v_fhcy {
  stop-color: var(--svg-color--655554, #655554);
  stop-opacity: 0;
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brgj7qtnd {
  cx: 10.18px;
  cy: 21.606px;
  r: 0.762px;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bxy9a_8wa {
  d: path("M20.61 25.837c.678-.6 1.716-.536 2.297.111l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.bzjertbri {
  fill-rule: evenodd;
  d: path("M15.972 4.392c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 0 1-1.16-1.028c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876a.775.775 0 1 1-1.112 1.08c-.735-.758-2.556-2.406-6.428-2.406");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cbnddobix {
  cx: 13.617px;
  cy: 9.874px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ccrydivzf {
  d: path("m11.186 26.33l2.71-1.12l-.67-1.62c-.41-1-1.1-1.691-1.988-2.11c-.465-.19-.717.06-.797.24c-.3.82-.081 2.136.085 3z");
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ch88whaiq {
  d: path("M18.254 9.493a.892.892 0 0 1 .86 1.127H17.39a.896.896 0 0 1 .864-1.128");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.czy-shbsj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.68 9.221c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.d_40zvxgb {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.467 2.776c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.572-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.debc6xrbn {
  stop-color: var(--svg-color--392726, #392726);
  stop-opacity: 0;
}

.dl8i_cb8p {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.678 10.344l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.614 0");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dsb0iwt3f {
  stop-color: var(--svg-color--503c3d, #503C3D);
  stop-opacity: 0;
}

.dw40nqbxs {
  d: path("M9.15 20.494a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7f-98b7z {
  stop-color: var(--svg-color--402825, #402825);
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ef5hhgevp {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.928 9.998c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.495-.025.6l.557.317c.651-.21 1.372-.24 2.078-.45");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.epr7emgds {
  fill: var(--svg-color--000, #000);
  d: path("M14.397 10.385a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.eygxffb5y {
  fill: var(--svg-color--000, #000);
  d: path("M17.743 10.385a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f5jafwbws {
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.f9mex4b1c {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.437c.096.054.144.22.081.348l-.668 1.391c-.181.388-.526.925-.809 1.177c-.687.638-1.466.645-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.324-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.438a.042.042 0 0 0-.027-.064l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.175a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.557.514 1.049 1.08 1.04c.574-.008.81-1.664.81-1.062v.467c0 .029.028.049.055.04l.458-.156q.112-.042.223-.058l.036-.084l1.043.853c.063-.129.19-.198.295-.152c.711.327.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.695 2.682-1.36");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.ff1dam-wq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.461 9.221c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fo-imacds {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g-9p05b4a {
  d: path("M21.48 25.323c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.ghbh5kb8u {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.477 6.386l-1.426.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.844 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.gi1u-g02v {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.673 8.79l-.005.002a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 0 1-.093.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.456.193");
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-5x17bxj {
  d: path("M9.984 15.883c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.hbd2-pbjl {
  stop-color: var(--svg-color--483d53, #483D53);
  stop-opacity: 0;
}

.hbyh_lbnn {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.82l.907 1.18");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hej-omb_k {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.789c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i3d34pb2k {
  d: path("M13.886 9.493a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.igts4bbee {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M11.001 4.579c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iw2-npbkp {
  d: path("M15.467 2.776c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.572-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
}

.j-elh2uvv {
  cx: 9.168px;
  cy: 20.528px;
  r: 0.762px;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jbqj6h9zn {
  d: path("M16.095 15.347h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jtc6ijb6j {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.055c.324 0 .758.376.758.86v.944");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k9pkqhbzh {
  d: path("M19.05 10.268a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcwstyspx {
  d: path("m20.799 26.33l-2.71-1.12l.67-1.62c.41-1 1.1-1.691 1.987-2.11c.466-.19.718.06.798.24c.3.82.081 2.136-.085 3z");
}

.kldnr3qau {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.07 13.479c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l_bchub-s {
  d: path("M11.001 4.579c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll2igknmu {
  d: path("m15.688 10.206l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lux6k2ifl {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.173c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.174.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m7an_cnhm {
  stop-color: var(--svg-color--655554, #655554);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mgnzdeb8x {
  d: path("M11.404 11.64a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.my40ihbtn {
  d: path("M10.983 9.304h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.12 3.073c-.122 2.802-2.311 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n35wtib-j {
  d: path("M14.701 10.28c0-.288-.234-.48-.298-.538l-.288.279l.178.36z");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nj7exebgj {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.386a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.nn1bribyc {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.802 8.332l-.138.23za.268.268 0 0 1-.276.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005l.003.002z");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.ntrmoswfw {
  d: path("M8.528 22.789c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.nvtd19bkp {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.212 9.998c.266-.467.67-.835 1.538-.835c.38 0 .746.105 1.072.368c.27.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.nw78dlb5d {
  cx: 13.617px;
  cy: 9.874px;
  rx: 0.39px;
  ry: 0.197px;
}

.nwmok1m8m {
  stop-color: var(--svg-color--392726, #392726);
}

.nx_ul7bge {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.404 11.64a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.o_6gh_hdi {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.07 13.479c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.o110mgbff {
  d: path("M23.457 22.789c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.o2j9ljphc {
  d: path("m13.196 29.96l-2.547-3.836l5.25-3.476l5.828 2.91l-2.922 4.403z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7b0b7x3a {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 26.002c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p1bwqsbsy {
  d: path("M20.897 12.176a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.p1f9bl61w {
  stop-color: var(--svg-color--2f1921, #2F1921);
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pjsve8bpd {
  d: path("M20.897 11.64a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq2t7lb5q {
  stop-color: var(--svg-color--543a37, #543A37);
}

.pulj51b3e {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.688 10.206l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxplm-b5k {
  d: path("M21.29 7.174c-.826-2.725-3.536-3.278-6.286-2.938c2.75.215 4.25 1.223 5.125 2.938z");
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.s623_lb_x {
  fill-rule: evenodd;
  d: path("M23.255 11.977c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.527-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233A3.3 3.3 0 0 0 16.07 2.04a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.26 3.26 0 0 0-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.012l1.199 2.355c.123 2.803 1.217 0 3.888 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.s9dopkbsv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.874c.395.01 1.357-.063 2.05-.441");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.shep8_bdh {
  d: path("M27 29.961v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.586 5 23.761 5 28.961v1z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tf_jinbsn {
  d: path("M11.385 12.176a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tpcvtjbvk {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.789c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uct9hwfmk {
  stop-color: var(--svg-color--503c3d, #503C3D);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ujsezfbfk {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.01 8.195c.322-.079 1.124-.04 1.66.344");
}

.ukkpznbub {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.897 11.64a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.uois0-_io {
  d: path("M16.425 15.347c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uu1nbqb1f {
  stop-color: var(--svg-color--231c22, #231C22);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v1t30ybxu {
  d: path("M18.189 9.681c.063.085-.07.19-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v7knejbmk {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.219 8.195c-.323-.079-1.125-.04-1.661.344");
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w0lgbgbhh {
  d: path("M5.062 16.46c0-8.812 4.89-13.218 10.922-13.218s10.922 4.219 10.922 13.219v13.5H5.062z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wn7tf0b0a {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.602c.307.135.83.615.461 1.453");
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x0qjlw0mb {
  d: path("M11.39 25.837c-.678-.6-1.716-.536-2.298.111l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.x3lhf8m8j {
  stop-color: var(--svg-color--2f1921, #2F1921);
  stop-opacity: 0;
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkb10lt3q {
  stop-color: var(--svg-color--231c22, #231C22);
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xlj1v1b_n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.189 9.681c.063.085-.07.19-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xv596dowm {
  d: path("M10.52 25.323c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yjp69hbuv {
  fill-rule: evenodd;
  d: path("M13.709 24.364a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.667l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.182l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yvn7twbfp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.179 4.025c.023.243.235 1.156.545 1.71");
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_qiivm8v {
  d: path("M15.993 25.254a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
