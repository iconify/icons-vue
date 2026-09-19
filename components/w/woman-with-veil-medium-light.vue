<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLUzBbQ)"><path fill="url(#i0OoAfd)" class="mqb05687l"/><path fill="url(#i1rSfob)" class="mqb05687l"/><path fill="url(#ixnuIHb)" class="mqb05687l"/></g><g filter="url(#iHCc17b)"><path fill="url(#icrRyde)" class="ewoa30b-w"/></g><g filter="url(#iSDwGbe)"><path fill="url(#iSfQ03d)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#iYtZdvr)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#iTdYL7b)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#i2ukifd)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#idCye0l)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#i4diJHc)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#iL7zVhb)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#inYTnrc)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#iimXQCc)" clip-rule="evenodd" class="xnuta16kd"/><path fill="url(#iDADLTc)" clip-rule="evenodd" class="xnuta16kd"/></g><path fill="url(#igtP7Fe)" class="jvp9atkai"/><path fill="url(#iYDUqge)" class="jvp9atkai"/><path fill="url(#izeIINe)" class="jvp9atkai"/><path fill="url(#iXPiQUH)" class="jvp9atkai"/><g filter="url(#iQmDe2c)"><path class="nopd-1b9s"/></g><g filter="url(#iIXMTKd)"><path class="r6l55i_4q"/></g><g filter="url(#iuzEHEd)"><path fill="url(#iKJ3Xoe)" class="py5bv0rkk"/><path fill="url(#ivg1Ikc)" class="py5bv0rkk"/><path fill="url(#iscabub)" class="py5bv0rkk"/></g><g filter="url(#i67m1fe)"><path fill="url(#i1lWTtc)" class="atew2hbdc"/><path fill="url(#i59LdEe)" class="atew2hbdc"/><path fill="url(#izcZxee)" class="atew2hbdc"/></g><g filter="url(#iUCpM9c)"><path fill="url(#ial3oOc)" class="bbgki1bfw"/><path fill="url(#i9dkL1b)" class="bbgki1bfw"/><path fill="url(#ijmwXxd)" class="bbgki1bfw"/><path fill="url(#irTNR1c)" class="bbgki1bfw"/><path fill="url(#ikBfpad)" class="bbgki1bfw"/></g><path fill="url(#ieEWOTY)" class="y8hbrabeg"/><path fill="url(#ihcsR2c)" class="y8hbrabeg"/><g filter="url(#iYvw2Vs)"><path class="ya0iv-beu"/></g><g filter="url(#iUpY3jb)"><path fill="url(#iABPZXr)" class="h2efu0gar"/><path fill="url(#idQbHhe)" class="h2efu0gar"/></g><g filter="url(#iufUZcv)"><path fill="url(#iHq7Dhc)" class="j-c82z2ln"/><path fill="url(#iunNcWc)" class="j-c82z2ln"/></g><circle fill="url(#ikD8RDb)" class="bwmbdw17c"/><circle fill="url(#iROR9te)" class="bwmbdw17c"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.944 20.382)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.944 20.382)" class="movji7bnz"/><circle fill="url(#ibmXSGe)" class="ks6pj6ttg"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.995 21.44)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.995 21.44)" class="movji7bnz"/><path fill="url(#iuDkcab)" class="u39qkx-pa"/><g filter="url(#inhYsWY)"><path class="qs28tayes"/><path fill="url(#ijRHKZj)" class="jpzbh3jhy"/><path fill="url(#isJW11E)" class="jpzbh3jhy"/><path fill="url(#iOXOAlc)" class="jpzbh3jhy"/><path fill="url(#iSBgxOe)" class="jpzbh3jhy"/><path fill="url(#ixzIkBa)" class="jpzbh3jhy"/></g><path fill="url(#ip4CRNe)" class="koqxyqbdi"/><g filter="url(#iOtsaNc)"><path class="etwia6bvl"/><path fill="url(#ic2Gj8b)" class="f4c6zpbov"/><path fill="url(#invo78b)" class="f4c6zpbov"/></g><g filter="url(#iaQXnzb)"><path class="r98f_9hgc"/><path fill="url(#isncYTb)" class="wk8as4bla"/><path fill="url(#iWDFm2d)" class="wk8as4bla"/><path fill="url(#i0QRQhc)" class="wk8as4bla"/><path fill="url(#iNbB5ok)" class="wk8as4bla"/><path fill="url(#iG5Tjmd)" class="wk8as4bla"/></g><g filter="url(#iG27R2t)"><path fill="url(#iLAguPc)" clip-rule="evenodd" class="r6v7z4qzu"/></g><g filter="url(#i5ccv5g)"><path class="v--u1j2rl"/></g><g filter="url(#ioEyDsd)"><path fill="url(#iNkIilb)" class="jk7_-kbdf"/><path fill="url(#iOqt4Ed)" class="jk7_-kbdf"/></g><g filter="url(#iW0i0rd)"><path stroke="url(#iylSckn)" class="hyzl2mbtc"/></g><g filter="url(#iozbauc)"><path stroke="url(#iEC7Zqq)" class="h8qijybxf"/></g><g filter="url(#iE7d2vd)"><path stroke="url(#iInGlyb)" class="bvhkjlw8p"/></g><g filter="url(#ixe3V2d)"><path stroke="url(#iLiJfOc)" class="hi6v-o9ho"/></g><g filter="url(#it9bW5y)"><path fill="url(#iVX1s1b)" class="lmam3fzym"/></g><g filter="url(#iH8z3gb)"><path fill="url(#iv6Zahm)" class="zhw2ckbqt"/><path fill="url(#iGo3GXb)" class="zhw2ckbqt"/></g><g filter="url(#iZS2hzb)"><path class="knl06rx9z"/><path fill="url(#imdfgLd)" class="qqwrg9bkf"/></g><g filter="url(#iVrxiyd)"><path class="j_59j8b9p"/><path fill="url(#in6s0Pb)" class="apsukih8l"/></g><g filter="url(#iL34iFJ)"><path fill="url(#iDN6mjb)" class="a8pt8kbxl"/><path fill="url(#ile1epb)" class="a8pt8kbxl"/><path fill="url(#ifk5nPb)" class="a8pt8kbxl"/><path fill="url(#icaLPPb)" class="a8pt8kbxl"/><path fill="url(#ib4Z9Xb)" class="a8pt8kbxl"/><path fill="url(#iyOakPc)" class="a8pt8kbxl"/><path fill="url(#iYPwnPc)" class="a8pt8kbxl"/></g><path fill="url(#iG7DPGc)" class="tmdz68phx"/><path fill="url(#ig6kZbm)" class="tmdz68phx"/><g filter="url(#iPaYkAd)"><path class="r-7_l6b0g"/></g><g filter="url(#imqfulp)"><path class="h4izhcbjz"/><path fill="url(#iWYnIJc)" class="l023bupck"/><path fill="url(#if4BoSc)" class="l023bupck"/><path fill="url(#itc8Jsc)" class="l023bupck"/></g><g filter="url(#i6Xi2ie)"><path fill="url(#ikNUMWb)" class="m8-c4lgnm"/></g><g filter="url(#iKPoTvm)"><path stroke="url(#iK82jpb)" class="y-sdcsbow"/></g><path class="lger42bvj"/><g filter="url(#iA4Qxbc)"><path class="wvm1pwb0w"/></g><g filter="url(#i9y1xac)"><path class="kdr_z5bul"/></g><g filter="url(#iXXBMLd)"><path class="ylo4g4tzq"/></g><g filter="url(#ico0d0P)"><path clip-rule="evenodd" class="tufp6t8qt"/></g><path class="hm6a_cbtt"/><path fill="url(#iR766UN)" class="t4sc96bmo"/><path class="ax1jbac3o"/><g filter="url(#i4NTzMc)"><path class="a0ou_xf0m"/><path fill="url(#iJ6Si3d)" class="dz8g1v6pi"/></g><g filter="url(#iKhhUId)"><path fill="url(#iYRofbb)" class="aslkmrbdl"/></g><path class="basc9ybqb"/><path fill="url(#iig7nUb)" class="arwzgfb_f"/><path class="hakxci-hb"/><g filter="url(#in9jxCO)"><path fill="url(#igt5UIs)" class="tsndh5vhq"/></g><g filter="url(#iAkruKV)"><ellipse transform="rotate(-27.914 13.58 9.885)" class="eqx66zb7m"/><ellipse fill="url(#i6hZlVb)" transform="rotate(-27.914 13.58 9.885)" class="u53j9vbss"/></g><g filter="url(#i33alDV)"><path class="v-twjhqyb"/></g><g filter="url(#iGVYXUc)"><path class="t1xdb585j"/></g><g filter="url(#ig5jZLc)"><path fill="url(#iL6ChOc)" class="wn7r18b9c"/><path fill="url(#i9wm4zd)" class="wn7r18b9c"/></g><g filter="url(#iqAHRvc)"><path fill="url(#i8pnIEb)" class="qv0t8xnkk"/><path fill="url(#i3dc05c)" class="qv0t8xnkk"/><path fill="url(#i2x0qgd)" class="qv0t8xnkk"/></g><g filter="url(#iXvHryb)"><path stroke="url(#iZNW6Rd)" class="zcz4fwbqv"/></g><g filter="url(#iATn4ee)"><path fill="url(#iWLlnOb)" class="nxxn0veax"/></g><g filter="url(#i4EJgae)"><path fill="url(#ilXnLCM)" clip-rule="evenodd" class="yc2kdhbaf"/><path fill="url(#iMv3eHc)" clip-rule="evenodd" class="yc2kdhbaf"/></g><defs><radialGradient id="i1rSfob" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.79 7.046)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="ixnuIHb" cx="0" cy="0" r="1" gradientTransform="matrix(6.93747 -5.37505 4.67308 6.03145 5.613 25.638)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iYtZdvr" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.725 16.398)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iTdYL7b" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.286 11.642)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="i2ukifd" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.17 8.886)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="idCye0l" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.786 8.31)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i4diJHc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.375 4.008)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iL7zVhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.194 3.005)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="inYTnrc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.702 7.152)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iimXQCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.541 9.726)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iDADLTc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.273 12.509)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="igtP7Fe" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.168 15.722)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="izeIINe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.788 27.98)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="iXPiQUH" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.882 24.136)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="ivg1Ikc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.382 25.774)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iscabub" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.654 14.619)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i59LdEe" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.789 27.276)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="izcZxee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.753 26.839)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ial3oOc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.557 21.558)" gradientUnits="userSpaceOnUse"><stop class="rytnnmv8a"/><stop offset="1" class="b3fwc4m_l"/></radialGradient><radialGradient id="i9dkL1b" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.755 16.606)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="v0p7hcb9x"/><stop offset="1" class="licq-dbtd"/></radialGradient><radialGradient id="ijmwXxd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.35483 1.0116 -.4299 -1.4257 16.032 16.19)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="fotkl_b9q"/><stop offset="1" class="ia04nc2ae"/></radialGradient><radialGradient id="irTNR1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.61 20.78)" gradientUnits="userSpaceOnUse"><stop class="qe7efdbrr"/><stop offset="1" class="ox8o7cb9c"/></radialGradient><radialGradient id="ikBfpad" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.361 16.673)" gradientUnits="userSpaceOnUse"><stop class="ko0wcdkuo"/><stop offset="1" class="qqn01fflj"/></radialGradient><radialGradient id="ieEWOTY" cx="0" cy="0" r="1" gradientTransform="matrix(6.15625 3.625 -4.70622 7.99244 12.6 25.605)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="idQbHhe" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.159 4.873)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iunNcWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.27 27.276)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="ikD8RDb" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.333 11.79)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iROR9te" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.4 14.594)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ibmXSGe" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.37 12.647)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iuDkcab" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.334 19.37)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="ijRHKZj" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.255 20.226)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="isJW11E" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.506 22.98)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iOXOAlc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.178 9.2)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iSBgxOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.304 24.777)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="ixzIkBa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.335 24.558)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="ip4CRNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.553 21.777)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="ic2Gj8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.32 22.683)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="invo78b" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.614 20.696)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="isncYTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.82 21.261)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iWDFm2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.31 22.948)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iLAguPc" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.33 16.629)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iNkIilb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.412 23.823)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iOqt4Ed" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.757 25.21)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iv6Zahm" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.072 11.017)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iGo3GXb" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.094 8.796)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="imdfgLd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.524 -52.202)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="in6s0Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.366 10.578)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iDN6mjb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.892 10.04)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="ile1epb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.933 10.738)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ifk5nPb" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.853 16.822)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="icaLPPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.15848 -9.70376 0 16.033 9.753)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="kkp-cwb2q"/><stop offset="1" class="l5j3h7bgj"/></radialGradient><radialGradient id="ib4Z9Xb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.92 6.745)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iyOakPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.334 9.622)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iYPwnPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.114 9.709)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iG7DPGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.128 11.11)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="ig6kZbm" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.533 4.534)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iWYnIJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.817 11.837)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iR766UN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.215 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iJ6Si3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.986 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iig7nUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.85 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6hZlVb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.803 -1.576)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iL6ChOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.075 4.33)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i9wm4zd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.317 4.564)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i8pnIEb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.943 2.653)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i3dc05c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.346 3.826)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i2x0qgd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.394 -.45)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iMv3eHc" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.688 8.582)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iLUzBbQ" width="21.944" height="26.818" x="4.874" y="3.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iHCc17b" width="12.631" height="14.916" x="9.51" y="8.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/><feGaussianBlur result="effect2_foregroundBlur_4002_3419" stdDeviation=".05"/></filter><filter id="iSDwGbe" width="15.268" height="15.768" x="8.523" y="1.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iQmDe2c" width="5.874" height="5.537" x="7.018" y="23.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".5"/></filter><filter id="iIXMTKd" width="4.979" height="4.054" x="18.536" y="24.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".5"/></filter><filter id="iuzEHEd" width="2.973" height="2.006" x="21.495" y="23.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="i67m1fe" width="3.281" height="2" x="20.494" y="25.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iUCpM9c" width="13.965" height="11.381" x="9.175" y="12.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.560784 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iYvw2Vs" width="10.996" height="6.432" x="11.958" y="21.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".5"/></filter><filter id="iUpY3jb" width="2.973" height="2.006" x="7.683" y="23.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iufUZcv" width="3.266" height="2" x="8.391" y="25.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="inhYsWY" width="6.218" height="6.789" x="8.369" y="19.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3419" result="effect2_innerShadow_4002_3419"/></filter><filter id="iOtsaNc" width="6.218" height="6.639" x="17.599" y="19.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3419" result="effect2_innerShadow_4002_3419"/></filter><filter id="iaQXnzb" width="6.702" height="6.417" x="12.708" y="20.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iG27R2t" width="6.703" height="6.517" x="12.658" y="20.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".15"/></filter><filter id="i5ccv5g" width="3.2" height="3.2" x="14.296" y="22.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".25"/></filter><filter id="ioEyDsd" width="2.35" height="2.35" x="14.918" y="23.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iW0i0rd" width="1.458" height="2.505" x="15.874" y="20.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="iozbauc" width="1.723" height="1.924" x="16.965" y="24.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="iE7d2vd" width="1.368" height="2.217" x="18.129" y="22.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="ixe3V2d" width="3.55" height="1.942" x="15.196" y="17.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".25"/></filter><filter id="it9bW5y" width="3.368" height="3.468" x="9.738" y="8.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iH8z3gb" width="3.218" height="3.468" x="19.251" y="8.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iZS2hzb" width="3.148" height="3.148" x="19.286" y="9.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".25"/></filter><filter id="iVrxiyd" width="2.948" height="2.948" x="9.892" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".2"/></filter><filter id="iL34iFJ" width="10.191" height="11.127" x="10.937" y="5.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iPaYkAd" width="2.877" height="3.682" x="14.432" y="9.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".25"/></filter><filter id="imqfulp" width="2.377" height="3.182" x="14.844" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="i6Xi2ie" width="2.377" height="3.182" x="14.844" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="iKPoTvm" width="3.702" height="1.526" x="14.181" y="12.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".05"/></filter><filter id="iA4Qxbc" width="3.001" height="1.286" x="16.975" y="9.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="i9y1xac" width="3.001" height="1.286" x="12.089" y="9.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="iXXBMLd" width="2.453" height="1.091" x="12.224" y="7.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="ico0d0P" width="2.453" height="1.091" x="17.642" y="7.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><filter id="i4NTzMc" width=".787" height=".696" x="17.48" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".05"/></filter><filter id="iKhhUId" width=".891" height=".913" x="18.32" y="9.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".1"/></filter><filter id="in9jxCO" width=".986" height="1.04" x="13.877" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".1"/></filter><filter id="iAkruKV" width=".913" height=".704" x="13.123" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".05"/></filter><filter id="i33alDV" width="2.261" height=".978" x="17.672" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".1"/></filter><filter id="iGVYXUc" width="2.261" height=".978" x="12.22" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".1"/></filter><filter id="ig5jZLc" width="4.287" height="5.25" x="9.773" y="3.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".25"/></filter><filter id="iqAHRvc" width="8.914" height="5.78" x="12.715" y="2.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".125"/></filter><filter id="iXvHryb" width="1.145" height="2.31" x="12.841" y="3.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".1"/></filter><filter id="iATn4ee" width="8.285" height="5.027" x="14.029" y="3.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3419" stdDeviation=".5"/></filter><filter id="i4EJgae" width="15.448" height="4.54" x="8.308" y="2.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3419"/></filter><linearGradient id="i0OoAfd" x1="26.818" x2="11.612" y1="11.513" y2="21.513" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="icrRyde" x1="20.725" x2="10.413" y1="17.386" y2="17.386" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iSfQ03d" x1="20.726" x2="13.921" y1="3.625" y2="16.23" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iYDUqge" x1="14.913" x2="14.913" y1="30.855" y2="29.573" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iKJ3Xoe" x1="23.675" x2="21.893" y1="25.777" y2="24.366" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="i1lWTtc" x1="22.975" x2="21.194" y1="27.361" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ihcsR2c" x1="12.678" x2="13.28" y1="29.245" y2="28.901" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iABPZXr" x1="7.882" x2="9.386" y1="24.26" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iHq7Dhc" x1="9.088" x2="10.868" y1="27.36" y2="25.675" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i0QRQhc" x1="14.944" x2="16.725" y1="27.124" y2="22.855" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iNbB5ok" x1="13.382" x2="17.007" y1="22.886" y2="23.573" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iG5Tjmd" x1="17.257" x2="16.35" y1="26.886" y2="25.136" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iylSckn" x1="16.503" x2="16.503" y1="20.808" y2="22.815" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iEC7Zqq" x1="17.311" x2="18.178" y1="24.862" y2="26.065" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iInGlyb" x1="18.754" x2="18.754" y1="22.394" y2="24.011" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iLiJfOc" x1="16.158" x2="20.142" y1="19.006" y2="17.834" gradientUnits="userSpaceOnUse"><stop class="cylb5xhsz"/><stop offset="1" class="zcstuupfv"/></linearGradient><linearGradient id="iVX1s1b" x1="9.738" x2="12.697" y1="10.665" y2="10.665" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="if4BoSc" x1="14.986" x2="15.841" y1="11.854" y2="11.959" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="itc8Jsc" x1="16.033" x2="16.033" y1="12.708" y2="12.098" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ikNUMWb" x1="16.033" x2="16.033" y1="9.767" y2="11.373" gradientUnits="userSpaceOnUse"><stop class="ecoejxh_i"/><stop offset="1" class="i4jn3rzxn"/></linearGradient><linearGradient id="iK82jpb" x1="15.304" x2="15.756" y1="14.185" y2="13.313" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iYRofbb" x1="18.992" x2="18.679" y1="10.035" y2="10.228" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igt5UIs" x1="14.594" x2="14.28" y1="10.035" y2="10.228" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZNW6Rd" x1="13.141" x2="13.686" y1="4.38" y2="5.654" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iWLlnOb" x1="20.658" x2="13.033" y1="6.907" y2="4.626" gradientUnits="userSpaceOnUse"><stop class="ptti8-hob"/><stop offset="1" class="wlnfmibbb"/></linearGradient><linearGradient id="ilXnLCM" x1="20.507" x2="8.569" y1="3.635" y2="7.323" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil-medium-light" /></template>
<style>
.a0ou_xf0m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.151 9.692c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.a8pt8kbxl {
  d: path("m10.947 9.05l-.01-.306c.02-.95.575-1.316.81-1.439l.052-.02l.05-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.apsukih8l {
  d: path("M11.366 11.652a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.arwzgfb_f {
  d: path("M13.848 9.504a.892.892 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.892");
}

.aslkmrbdl {
  d: path("M19.011 10.28a.84.84 0 0 0-.23-.464l-.26.286l.116.228z");
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atew2hbdc {
  d: path("M20.636 25.792c.678-.6 1.716-.535 2.297.112l.69.734c.062.068.083.205-.024.271c-.91.563-1.995.492-2.66-.27l-.42-.584a.11.11 0 0 1 .01-.15z");
}

.ax1jbac3o {
  fill: var(--svg-color--000, #000);
  d: path("M17.706 10.396c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.b3fwc4m_l {
  stop-color: var(--svg-color--da9f7c, #DA9F7C);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.basc9ybqb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.642 9.232c-.653 0-1.205.45-1.355 1.06a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.bbgki1bfw {
  d: path("M9.175 20.45a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.863-3.518");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bvhkjlw8p {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.46 22.558c.307.135.83.615.46 1.453");
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bwmbdw17c {
  cx: 9.193px;
  cy: 20.484px;
  r: 0.762px;
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cylb5xhsz {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.dz8g1v6pi {
  d: path("M18.151 9.692c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ecoejxh_i {
  stop-color: var(--svg-color--edb596, #EDB596);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqx66zb7m {
  cx: 13.579px;
  cy: 9.885px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.etwia6bvl {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.483 22.745c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.1.12-.144.112-.118-.035c.248-1.376.009-3.139-.846-3.532c-.126-.055-.278.027-.354.183l-.754 1.631c-.044.107-.088.204-.132.311c-.112.293-.304.839-.337 1.135c-.152 1.231.46 2.09 1.431 2.537c.893.415 1.83.406 2.655-.36c.34-.302.754-.948.973-1.414z");
}

.ewoa30b-w {
  d: path("M10.01 15.84c0-4.854 2.693-7.281 6.016-7.281s6.015 2.323 6.015 7.28v7.436H10.01z");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f4c6zpbov {
  d: path("M23.483 22.745c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.1.12-.144.112-.118-.035c.248-1.376.009-3.139-.846-3.532c-.126-.055-.278.027-.354.183l-.754 1.631c-.044.107-.088.204-.132.311c-.112.293-.304.839-.337 1.135c-.152 1.231.46 2.09 1.431 2.537c.893.415 1.83.406 2.655-.36c.34-.302.754-.948.973-1.414z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fotkl_b9q {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
}

.ft5dv1b6b {
  fill: none;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h2efu0gar {
  d: path("M10.545 25.279c-.062-.898-.842-1.586-1.72-1.534l-.99.058c-.122 0-.163.158-.15.207c.177.967.962 1.703 2 1.633l.768-.097a.11.11 0 0 0 .103-.118z");
}

.h4izhcbjz {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.65 10.217l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.645-.377-.765 0");
}

.h8qijybxf {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.374 24.776l.906 1.18");
}

.hakxci-hb {
  fill: var(--svg-color--000, #000);
  d: path("M14.36 10.396a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.hi6v-o9ho {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.946 18.83c.395.01 1.357-.063 2.05-.441");
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hm6a_cbtt {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.424 9.232c.653 0 1.204.45 1.354 1.06a.274.274 0 0 1-.267.34H17.28a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hyzl2mbtc {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.124 21.01c.324 0 .758.377.758.86v.945");
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i4jn3rzxn {
  stop-color: var(--svg-color--edb596, #EDB596);
  stop-opacity: 0;
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.ia04nc2ae {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
  stop-opacity: 0;
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j_59j8b9p {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.366 11.652a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.j-c82z2ln {
  d: path("M11.416 25.792c-.679-.6-1.717-.535-2.298.112l-.69.734c-.062.068-.04.22.024.271c.91.563 1.996.492 2.66-.27l.42-.584a.11.11 0 0 0-.01-.15z");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jk7_-kbdf {
  d: path("M16.018 25.21a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jpzbh3jhy {
  d: path("M8.553 22.745c-.076-.155-.018-.354.098-.418c.854-.404 2.334.552 3.223 1.633c.098.12.143.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.354.183l.754 1.631c.044.107.088.204.132.311c.112.293.304.839.337 1.135c.152 1.231-.46 2.09-1.431 2.537c-.893.415-1.83.406-2.655-.36c-.34-.302-.754-.948-.972-1.414z");
}

.jvp9atkai {
  d: path("M27.026 29.917v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61c-4.85 1.14-8.46 5.315-8.46 10.515v1z");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kdr_z5bul {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.89 10.008c-.265-.466-.668-.835-1.537-.835c-.38 0-.747.105-1.072.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.kkp-cwb2q {
  stop-color: var(--svg-color--c4847d, #C4847D);
  stop-opacity: 0;
}

.knl06rx9z {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.86 11.652a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ko0wcdkuo {
  stop-color: var(--svg-color--db977c, #DB977C);
}

.koqxyqbdi {
  d: path("m20.825 26.287l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.717.058.797.238c.3.82.082 2.137-.084 3.002z");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ks6pj6ttg {
  cx: 10.205px;
  cy: 21.562px;
  r: 0.762px;
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l023bupck {
  d: path("m15.65 10.217l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.645-.377-.765 0");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l5j3h7bgj {
  stop-color: var(--svg-color--b8736a, #B8736A);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lger42bvj {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.033 13.49c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.licq-dbtd {
  stop-color: var(--svg-color--d6927c, #D6927C);
  stop-opacity: 0;
}

.lmam3fzym {
  d: path("M11.347 12.187a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m8-c4lgnm {
  d: path("m15.65 10.049l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.645-.377-.765 0");
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mqb05687l {
  d: path("M4.974 16.45c0-8.812 4.89-13.219 10.922-13.219s10.922 4.22 10.922 13.22V29.95H4.974z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nopd-1b9s {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.16 24.129c.878-.052 1.658.636 1.72 1.534l.008.116c.31.043.611.174.863.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.833-2.661.27c-.064-.05-.086-.202-.023-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.014-.049.028-.207.149-.207z");
}

.nxxn0veax {
  d: path("M21.315 7.063c-.825-2.725-3.536-3.277-6.286-2.937c2.751.214 4.25 1.223 5.125 2.937z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
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

.ox8o7cb9c {
  stop-color: var(--svg-color--db9f70, #DB9F70);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.ptti8-hob {
  stop-color: var(--svg-color--ebc79c, #EBC79C);
}

.py5bv0rkk {
  d: path("M21.506 25.279c.063-.898.842-1.586 1.72-1.534l.99.058c.122 0 .163.158.15.207c-.177.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qe7efdbrr {
  stop-color: var(--svg-color--db9f70, #DB9F70);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qqn01fflj {
  stop-color: var(--svg-color--db977c, #DB977C);
  stop-opacity: 0;
}

.qqwrg9bkf {
  d: path("M20.86 11.652a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.qs28tayes {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.553 22.745c-.076-.155-.018-.354.098-.418c.854-.404 2.334.552 3.223 1.633c.098.12.143.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.354.183l.754 1.631c.044.107.088.204.132.311c.112.293.304.839.337 1.135c.152 1.231-.46 2.09-1.431 2.537c-.893.415-1.83.406-2.655-.36c-.34-.302-.754-.948-.972-1.414z");
}

.qv0t8xnkk {
  d: path("M15.43 2.787c-1.133-.25-2.347.955-2.465 1.374c1.542 3.62 3.91 3.276 6.537 2.984c1.573-.175 1.743.542 1.877.888c-.435-4.056-3.369-4.676-5.95-5.246");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r-7_l6b0g {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.64 10.355l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r6l55i_4q {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.714 25.958c.78-.46 1.786-.2 2.234.545l.538.852c.049.078.043.217-.074.261c-1 .38-2.053.105-2.56-.77l-.303-.652a.11.11 0 0 1 .038-.145z");
}

.r6v7z4qzu {
  fill-rule: evenodd;
  d: path("M13.734 24.32a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.618.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.02-.216.044-.404a.85.85 0 0 1 .8-.6c.531-.008.926.396.926 1v.561a.3.3 0 0 0 .397.284l.55-.187l.008-.003c.516-.193 1.022.047 1.16.56c.14.531-.184 1.092-.687 1.183l-.467.102a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.428.299-1.011.16-1.32-.295l-.316-.423a.3.3 0 0 0-.492.017l-.248.384l-.004.008a.91.91 0 0 1-1.294.33l-.002-.002a.917.917 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.195-.463l-.37-.067z");
}

.r98f_9hgc {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.738 23.157c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.215 1.373-.885 1.493l-.457.1a.05.05 0 0 0-.03.079l.308.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.082.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.358-.526a.05.05 0 0 0-.033-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rytnnmv8a {
  stop-color: var(--svg-color--f6bf99, #F6BF99);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t1xdb585j {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.181 8.205c-.322-.078-1.124-.039-1.66.345");
}

.t4sc96bmo {
  d: path("M18.217 9.504a.893.893 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tmdz68phx {
  d: path("M10.945 9.315h.013l-.01-.265l-.01-.306c.02-.95.573-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .46-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tsndh5vhq {
  d: path("M14.664 10.292c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.tufp6t8qt {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.764 8.342l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.013l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.989 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u39qkx-pa {
  d: path("m11.212 26.287l2.71-1.12l-.67-1.62c-.41-1-1.101-1.692-1.988-2.11c-.466-.191-.717.058-.797.238c-.3.82-.082 2.137.085 3.002z");
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u53j9vbss {
  cx: 13.579px;
  cy: 9.885px;
  rx: 0.39px;
  ry: 0.197px;
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v--u1j2rl {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.896 25.342a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v-twjhqyb {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.972 8.205c.323-.078 1.125-.039 1.66.345");
}

.v0p7hcb9x {
  stop-color: var(--svg-color--d6927c, #D6927C);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wk8as4bla {
  d: path("M12.738 23.157c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.215 1.373-.885 1.493l-.457.1a.05.05 0 0 0-.03.079l.308.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.082.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.358-.526a.05.05 0 0 0-.033-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wlnfmibbb {
  stop-color: var(--svg-color--ebc79c, #EBC79C);
  stop-opacity: 0;
}

.wn7r18b9c {
  d: path("M11.138 4.564c.621-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.679.235c-.452 1.676-2.162 1.425-2.497 2.682c-.151-1.492-.319-2.783.754-3.738");
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wvm1pwb0w {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.175 10.008c.265-.466.668-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.651-.21-1.372-.239-2.078-.45");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xnuta16kd {
  fill-rule: evenodd;
  d: path("M23.218 11.988a3.25 3.25 0 0 0 .323-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.011a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01A3.24 3.24 0 0 1 9.07 8.74l-.003.004a3.3 3.3 0 0 0-.22 3.245a.51.51 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.12-.982-.323-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.051l-.083.194c-.225.561-.656.99-1.19 1.234l-.05.02l-.052.021c-.236.123-.79.49-.81 1.439l.01.306z");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.y-sdcsbow {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.033 13.49c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345Z");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8hbrabeg {
  d: path("m13.221 29.917l-2.547-3.837l5.25-3.475l5.829 2.909l-2.922 4.403z");
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.ya0iv-beu {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.844 23.393c.097.053.145.219.082.348l-.668 1.39c-.182.388-.526.926-.81 1.177c-.686.639-1.466.646-2.21.3a2.4 2.4 0 0 1-.48-.291a.97.97 0 0 1-.408.892c-.466.325-1.078.16-1.39-.3l-.257-.343a.042.042 0 0 0-.068.002l-.202.312a.966.966 0 0 1-1.373.35a.97.97 0 0 1-.242-1.415l.298-.438a.042.042 0 0 0-.027-.064l-.308-.056a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.249-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.513 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .029.027.049.054.04l.459-.157q.111-.041.222-.057l.036-.085l1.043.854c.064-.13.19-.198.295-.152c.712.327.495-.417.289.728c-.022.122.015.13.097.03c.74-.9 1.971-1.696 2.682-1.36");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yc2kdhbaf {
  fill-rule: evenodd;
  d: path("M15.997 4.348c-3.811 0-5.694 1.656-6.333 2.38A.775.775 0 1 1 8.503 5.7c.881-.996 3.165-2.902 7.494-2.902c4.41 0 6.609 1.915 7.541 2.876a.775.775 0 1 1-1.113 1.079c-.734-.757-2.556-2.405-6.428-2.405");
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ylo4g4tzq {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.635 8.8l-.005.002a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.194");
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zcstuupfv {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
  stop-opacity: 0;
}

.zcz4fwbqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.141 4.036c.024.243.235 1.157.545 1.71");
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zhw2ckbqt {
  d: path("M20.86 12.187a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
