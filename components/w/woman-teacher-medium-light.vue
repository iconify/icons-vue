<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iigFQae)"><path fill="url(#iOvytEb)" class="ww-u-6o5x"/></g><path fill="url(#ig7DZHd)" class="h6t434-4p"/><path fill="url(#iqZ4BCe)" class="h6t434-4p"/><path fill="url(#iyBueDb)" class="h6t434-4p"/><g filter="url(#iM6rlgd)"><path stroke="url(#ivit6Yc)" class="lf-bul-6p"/></g><g filter="url(#i8JV0Lb)"><path fill="url(#ifaecNd)" class="pmbuwrbwv"/><path fill="url(#iKmEVeb)" class="pmbuwrbwv"/><path fill="url(#ioqsCPb)" class="pmbuwrbwv"/></g><g filter="url(#iPyNA4d)"><path fill="url(#i1BMoYU)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iezbunY)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iloiQcT)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iGtQ5Hb)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iTQoIAc)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iQ6lZZd)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#ib33hxd)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#ivGNs3b)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#icKkFuC)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iLxhQFB)" clip-rule="evenodd" class="o5hkefbwq"/><path fill="url(#iiCm04d)" clip-rule="evenodd" class="o5hkefbwq"/></g><path fill="url(#ifypaxe)" class="su97fabko"/><path fill="url(#iyv1Jdc)" class="su97fabko"/><path fill="url(#iLlJkWx)" class="su97fabko"/><path fill="url(#iXlnekc)" class="tf_vtpbnm"/><path fill="url(#i9aRpfc)" class="tf_vtpbnm"/><path fill="url(#ixcvsMc)" class="tf_vtpbnm"/><path fill="url(#iTH1rbb)" class="vgy50acyo"/><path fill="url(#iqgUGde)" class="vgy50acyo"/><path fill="url(#ijpHXRc)" class="hh8f61bxt"/><g filter="url(#iHJ1eAe)"><path fill="url(#i3OW3sc)" class="g-zghwb2b"/><path fill="url(#iaVgtAd)" class="g-zghwb2b"/><path fill="url(#i3haCjd)" class="g-zghwb2b"/><path fill="url(#ihfRE7U)" class="g-zghwb2b"/></g><g filter="url(#iIx6fuu)"><path fill="url(#ieOfqTd)" class="cylqej8yl"/><path fill="url(#iSHhunb)" class="cylqej8yl"/><path fill="url(#iy7Uavd)" class="cylqej8yl"/><path fill="url(#iu5EQ4u)" class="cylqej8yl"/></g><path fill="url(#idLXHxb)" class="zt-qvcc3y"/><g filter="url(#i99qlQc)"><path fill="url(#iOt9Cze)" class="wc5i2do8i"/><path fill="url(#iRs5Gwd)" class="wc5i2do8i"/></g><g filter="url(#iw5Qglb)"><path fill="url(#iGiWuWc)" class="svu_n61ll"/></g><path fill="url(#iE4GUdd)" class="i1-ophxps"/><path clip-rule="evenodd" class="p33iqucaj"/><path fill="url(#iaqZAxc)" clip-rule="evenodd" class="p5amjacbp"/><g filter="url(#izNX0De)"><path fill="url(#ie08g6x)" class="n5ywlebli"/><path fill="url(#ifijsmd)" class="n5ywlebli"/><path fill="url(#ijXuZHe)" class="n5ywlebli"/><path fill="url(#iuarBnc)" class="n5ywlebli"/><path fill="url(#iNBaREd)" class="n5ywlebli"/></g><g filter="url(#izX5qoc)"><path fill="url(#i3jk9ke)" class="d-4zt4b0n"/><path fill="url(#iPjH60b)" class="d-4zt4b0n"/><path fill="url(#ixk0nFb)" class="d-4zt4b0n"/><path fill="url(#iE57qMd)" class="d-4zt4b0n"/><path fill="url(#iY1RIlb)" class="d-4zt4b0n"/></g><path fill="url(#iuZOQ2d)" class="os-6q6bjn"/><path fill="url(#iIgeTbb)" class="i8-v2xbel"/><g filter="url(#i38IE2d)"><path stroke="url(#iS5dnBe)" class="toq52_0ol"/></g><g filter="url(#iG1ICtT)"><path stroke="url(#itSOiSc)" class="uqw44xe1t"/></g><g filter="url(#i4uhp0c)"><path stroke="url(#ijAI2Lb)" class="x8kkqybjp"/></g><g filter="url(#iJmPBMe)"><path stroke="url(#i1CVN8E)" class="dqoo1pb9u"/></g><g filter="url(#iLwGNlb)"><path stroke="url(#ipI6oZd)" class="kj_445bvl"/></g><g filter="url(#iU7RKWd)"><path stroke="url(#ioa6p7R)" class="c1fjaebok"/></g><g filter="url(#ihjTsQc)"><path fill="url(#iJ9Pyad)" class="nfzhu5bbl"/></g><g filter="url(#i4PgRnc)"><path fill="url(#i3Z8KJd)" class="hwblgdbjb"/><path fill="url(#iWsOwbb)" class="hwblgdbjb"/></g><g filter="url(#ij5qxUD)"><path class="dgmopr_zh"/><path fill="url(#iGUesnd)" class="q9z2zxzql"/></g><g filter="url(#i7EhGEe)"><path class="agzqafqtz"/><path fill="url(#i2Zk9ae)" class="rl_kduowq"/></g><g filter="url(#iHmYUPb)"><path fill="url(#iDEdKhK)" class="btf1q82gc"/><path fill="url(#iCmVhDe)" class="btf1q82gc"/><path fill="url(#izby5Jb)" class="btf1q82gc"/><path fill="url(#izrz6Hb)" class="btf1q82gc"/><path fill="url(#iLD2zPd)" class="btf1q82gc"/><path fill="url(#iYU9QEe)" class="btf1q82gc"/><path fill="url(#iFuJt3v)" class="btf1q82gc"/></g><path fill="url(#i3cUbhb)" class="bgt_x0cif"/><path fill="url(#igV0jQd)" class="bgt_x0cif"/><g filter="url(#itbvAlc)"><path class="zpn51dtjs"/></g><g filter="url(#i9Rhvkc)"><path class="ijm85hble"/><path fill="url(#it4CQ9d)" class="xsm2r-b6f"/><path fill="url(#iDf7kld)" class="xsm2r-b6f"/><path fill="url(#iAbcDMf)" class="xsm2r-b6f"/></g><path fill="url(#ir0Wxjc)" class="xsm2r-b6f"/><path fill="url(#i9lCrrc)" class="xsm2r-b6f"/><path stroke="url(#iKWAgmb)" class="ljsj1x_ip"/><g filter="url(#iYEoB1f)"><path class="jws7bwb2s"/></g><g filter="url(#ik7P2vR)"><path class="nibr25dfr"/></g><g filter="url(#igum6xb)"><path class="x8r2h-b0e"/></g><g filter="url(#iik6FHe)"><path clip-rule="evenodd" class="d1t689bgg"/></g><path class="yajmx8bkt"/><path fill="url(#iEpEPDd)" class="wledphbfk"/><path class="uom77qk9x"/><g filter="url(#iu0y9lb)"><path class="uf-ge482b"/><path fill="url(#iOFomsc)" class="gyhrvmbpf"/></g><g filter="url(#iueX7sb)"><path fill="url(#isBo4Id)" class="drmhdlb1v"/></g><path class="yo4qn9o0i"/><path fill="url(#inN8wUb)" class="zts3u4f8u"/><path class="kp9-98bbr"/><g filter="url(#it6pUBc)"><path fill="url(#iCbTQob)" class="q_vkqua2e"/></g><g filter="url(#iPEtEAe)"><ellipse transform="rotate(-27.914 13.515 10.008)" class="miy6sr-xa"/><ellipse fill="url(#iFfYrPd)" transform="rotate(-27.914 13.515 10.008)" class="hv7h32bkd"/></g><g filter="url(#iluJYAd)"><path class="qu23eebor"/></g><g filter="url(#ioZWq3c)"><path class="hutawke8n"/></g><g filter="url(#iZHsYNb)"><path fill="url(#izPUjKe)" class="tic9i85fu"/><path fill="url(#iS1glDb)" class="tic9i85fu"/></g><g filter="url(#iwtAc7c)"><path fill="url(#iARBG2b)" class="x11m1v6la"/><path fill="url(#iPvCBVI)" class="x11m1v6la"/><path fill="url(#iBcuGFb)" class="x11m1v6la"/></g><g filter="url(#iHZh6ob)"><path stroke="url(#ilmT3rb)" class="k_e-s8buu"/></g><g filter="url(#iYnA3Wd)"><path fill="url(#iI9DH7d)" class="ob12b5chv"/><path fill="url(#iyGq59d)" class="ob12b5chv"/></g><defs><radialGradient id="iqZ4BCe" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.095 6.924)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iyBueDb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.572 25.535)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="ioqsCPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.014 4.37)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iezbunY" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.661 16.52)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iloiQcT" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.21 11.68)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iGtQ5Hb" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.118 8.937)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iTQoIAc" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.722 8.354)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iQ6lZZd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.35 4.073)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ib33hxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.13 3.127)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="ivGNs3b" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.644 7.199)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="icKkFuC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.478 9.849)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iLxhQFB" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.21 12.63)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iiCm04d" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.367 15.394)scale(8.92883)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="ahi65f7eh"/><stop offset="1" class="lb6_n4jos"/></radialGradient><radialGradient id="ifypaxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.01 16.003)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iyv1Jdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.666 20.535)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iLlJkWx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.727 19.128)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iXlnekc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.004 28.285)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iqgUGde" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.468 29.833)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="ijpHXRc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 13.3779 15.197 19.047)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iaVgtAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.96409 21.24 19.494)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="i3haCjd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.145 5.16)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ihfRE7U" cx="0" cy="0" r="1" gradientTransform="matrix(.39392 .87431 -1.63655 .73735 17.731 15.853)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iSHhunb" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.525 20.41)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iu5EQ4u" cx="0" cy="0" r="1" gradientTransform="matrix(-.40353 .93196 -1.74446 -.75533 14.186 15.95)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="idLXHxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.44762 -2.52198 0 16.26 16.986)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="d8d9qvbdm"/><stop offset="1" class="rxhwz8-zs"/></radialGradient><radialGradient id="iOt9Cze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.646 23.821)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="vh6yi_hgr"/><stop offset="1" class="e4t4y8vlz"/></radialGradient><radialGradient id="iRs5Gwd" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.788 23.54)" gradientUnits="userSpaceOnUse"><stop class="vvq7hbbzt"/><stop offset="1" class="eb5hv9bjw"/></radialGradient><radialGradient id="iGiWuWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.103 24.063)" gradientUnits="userSpaceOnUse"><stop class="x109hm4su"/><stop offset="1" class="va5jmqb6u"/></radialGradient><radialGradient id="ifijsmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.197 25.415)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="ijXuZHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.213 26.696)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iuarBnc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.26 27.977)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iNBaREd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.33 29.337)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iPjH60b" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.26 25.415)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="ixk0nFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.197 26.696)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="iE57qMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.103 27.977)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="iY1RIlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.963 29.337)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="i3Z8KJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.008 11.14)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iWsOwbb" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.03 8.918)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iGUesnd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.833 -51.963)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i2Zk9ae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.302 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iDEdKhK" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.828 10.162)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iCmVhDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.87 10.86)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="izby5Jb" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.79 16.946)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="izrz6Hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 15.969 9.875)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="iLD2zPd" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.885 6.804)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iYU9QEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.27 9.744)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iFuJt3v" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.05 9.831)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="i3cUbhb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.064 11.232)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="igV0jQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.469 4.657)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="it4CQ9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.753 11.958)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i9lCrrc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.27 8.405)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iEpEPDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.15 10.103)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iOFomsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.923 10.187)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inN8wUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.787 10.103)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iFfYrPd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.831 -1.484)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izPUjKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.011 4.452)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iS1glDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.254 4.686)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iARBG2b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.88 2.775)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iPvCBVI" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.282 3.949)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iBcuGFb" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.398 -.37)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iyGq59d" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.208)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="iigFQae" width="27.98" height="21.09" x="2.014" y="4.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iM6rlgd" width="27.413" height="20.785" x="2.678" y="3.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".2"/></filter><filter id="i8JV0Lb" width="27.91" height="20.96" x="2.014" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iPyNA4d" width="15.268" height="15.768" x="8.46" y="1.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iHJ1eAe" width="2.797" height="14.499" x="18.064" y="15.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iIx6fuu" width="2.797" height="14.499" x="11.157" y="15.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="i99qlQc" width="2.1" height="3.39" x="20.957" y="23.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.752941 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iw5Qglb" width="2.1" height="3.29" x="8.96" y="23.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.611765 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="izNX0De" width="4.793" height="5.391" x="8.96" y="24.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="izX5qoc" width="4.793" height="5.591" x="18.464" y="24.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.435294 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.741176 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1665" result="effect2_innerShadow_4002_1665"/></filter><filter id="i38IE2d" width="2.222" height=".3" x="18.883" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iG1ICtT" width="2.222" height=".3" x="10.87" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="i4uhp0c" width="2.222" height=".3" x="18.883" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iJmPBMe" width="2.222" height=".3" x="10.87" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iLwGNlb" width="2.222" height=".3" x="18.883" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iU7RKWd" width="2.222" height=".3" x="10.87" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="ihjTsQc" width="3.368" height="3.468" x="9.674" y="9.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="i4PgRnc" width="3.218" height="3.468" x="19.187" y="8.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="ij5qxUD" width="3.148" height="3.148" x="19.222" y="9.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".25"/></filter><filter id="i7EhGEe" width="2.948" height="2.948" x="9.828" y="9.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".2"/></filter><filter id="iHmYUPb" width="10.191" height="11.127" x="10.873" y="5.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="itbvAlc" width="2.877" height="3.682" x="14.368" y="9.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".25"/></filter><filter id="i9Rhvkc" width="2.377" height="3.182" x="14.78" y="9.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".125"/></filter><filter id="iYEoB1f" width="3.001" height="1.285" x="16.911" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="ik7P2vR" width="3.001" height="1.285" x="12.025" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="igum6xb" width="2.453" height="1.091" x="12.161" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iik6FHe" width="2.453" height="1.091" x="17.578" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/></filter><filter id="iu0y9lb" width=".787" height=".696" x="17.417" y="9.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iueX7sb" width=".891" height=".913" x="18.256" y="9.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".1"/></filter><filter id="it6pUBc" width=".986" height="1.04" x="13.814" y="9.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".1"/></filter><filter id="iPEtEAe" width=".913" height=".705" x="13.059" y="9.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".05"/></filter><filter id="iluJYAd" width="2.661" height="1.378" x="17.408" y="7.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".2"/></filter><filter id="ioZWq3c" width="2.661" height="1.378" x="11.957" y="7.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".2"/></filter><filter id="iZHsYNb" width="4.287" height="5.25" x="9.709" y="3.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".25"/></filter><filter id="iwtAc7c" width="8.914" height="5.78" x="12.652" y="2.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".125"/></filter><filter id="iHZh6ob" width="1.145" height="2.31" x="12.777" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1665" stdDeviation=".1"/></filter><filter id="iYnA3Wd" width="10.29" height="4.16" x="10.894" y="8.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1665" result="effect2_innerShadow_4002_1665"/></filter><linearGradient id="iOvytEb" x1="11.828" x2="31.271" y1="4.659" y2="22.895" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="ig7DZHd" x1="30.072" x2="9.135" y1="13.347" y2="13.347" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="ivit6Yc" x1="13.447" x2="31.26" y1="3.6" y2="24.412" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="ifaecNd" x1="-4.897" x2="28.916" y1="25.691" y2="25.691" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iKmEVeb" x1="3.103" x2="3.103" y1="5.253" y2="23.691" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="i1BMoYU" x1="20.662" x2="13.857" y1="3.747" y2="16.352" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i9aRpfc" x1="25.183" x2="25.183" y1="30.505" y2="26.688" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="ixcvsMc" x1="22.416" x2="23.228" y1="29.316" y2="29.3" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iTH1rbb" x1="7.144" x2="9.538" y1="28.198" y2="28.198" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="i3OW3sc" x1="18.064" x2="20.86" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="ieOfqTd" x1="13.954" x2="11.157" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iy7Uavd" x1="12.119" x2="12.681" y1="16.988" y2="17.207" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iE4GUdd" x1="21.853" x2="17.478" y1="24.847" y2="24.847" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iaqZAxc" x1="10.324" x2="10.752" y1="23.628" y2="23.628" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="ie08g6x" x1="12.873" x2="8.572" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop class="oup8n6dpm"/><stop offset=".716" class="zw2whl-je"/></linearGradient><linearGradient id="i3jk9ke" x1="22.478" x2="18.664" y1="27.66" y2="27.66" gradientUnits="userSpaceOnUse"><stop class="d1gud5zvw"/><stop offset=".807" class="bku9lhrph"/></linearGradient><linearGradient id="iuZOQ2d" x1="10.791" x2="21.664" y1="22.003" y2="22.003" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iIgeTbb" x1="16.41" x2="16.41" y1="21.066" y2="22.238" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iS5dnBe" x1="19.033" x2="20.861" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="itSOiSc" x1="12.942" x2="10.744" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="ijAI2Lb" x1="19.033" x2="20.861" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="i1CVN8E" x1="12.942" x2="10.744" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="ipI6oZd" x1="19.033" x2="20.861" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="ioa6p7R" x1="12.942" x2="10.744" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="iJ9Pyad" x1="9.674" x2="12.633" y1="10.787" y2="10.787" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iDf7kld" x1="14.922" x2="15.777" y1="11.976" y2="12.081" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iAbcDMf" x1="15.969" x2="15.969" y1="12.83" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ir0Wxjc" x1="16.047" x2="16.047" y1="12.804" y2="12.665" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iKWAgmb" x1="15.24" x2="15.692" y1="14.307" y2="13.435" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="isBo4Id" x1="18.929" x2="18.615" y1="10.157" y2="10.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCbTQob" x1="14.53" x2="14.217" y1="10.157" y2="10.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilmT3rb" x1="13.078" x2="13.622" y1="4.502" y2="5.776" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iI9DH7d" x1="16.089" x2="16.089" y1="9.104" y2="12.885" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher-medium-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.agzqafqtz {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.302 11.774a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ahi65f7eh {
  stop-color: var(--svg-color--a0724c, #A0724C);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bgt_x0cif {
  d: path("M10.882 9.437h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.bi-ijln_l {
  stop-color: var(--svg-color--ab685c, #AB685C);
  stop-opacity: 0;
}

.bku9lhrph {
  stop-color: var(--svg-color--b97a6f, #B97A6F);
}

.btf1q82gc {
  d: path("m10.884 9.172l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.c1fjaebok {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 28.62H11.02");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.cylqej8yl {
  d: path("m12.678 16.07l-1.374 2.969c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.652z");
}

.d-4zt4b0n {
  d: path("M18.664 25.42a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.84.84 0 0 0-.303.668c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893h-2.842c-.475 0-.77.39-.778.76");
}

.d1gud5zvw {
  stop-color: var(--svg-color--f0c0a1, #F0C0A1);
}

.d1t689bgg {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.7 8.465l-.137.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.094-.528c.514-.09.989 0 1.329.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.d8d9qvbdm {
  stop-color: var(--svg-color--ac7d6a, #AC7D6A);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dgmopr_zh {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.796 11.774a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dqoo1pb9u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 27.355H11.02");
}

.drmhdlb1v {
  d: path("M18.948 10.4a.84.84 0 0 0-.232-.462l-.26.285l.118.229z");
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

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e4t4y8vlz {
  stop-color: var(--svg-color--c8926a, #C8926A);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eb5hv9bjw {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g-zghwb2b {
  d: path("m19.321 16.055l1.393 2.984c.09.19-.05.41-.26.41l-.964-.266c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.652z");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g1nxbnbrj {
  stop-color: var(--svg-color--e4b8a5, #E4B8A5);
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g8fj5qv-y {
  stop-color: var(--svg-color--d29c80, #D29C80);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.gyhrvmbpf {
  d: path("M18.087 9.815c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.h6t434-4p {
  d: path("M3.014 24.04V5.05h25.99v18.99z");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hh8f61bxt {
  d: path("M18.064 15.104h-4.11V30.05h4.11z");
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hutawke8n {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.117 8.328c-.322-.079-1.124-.04-1.66.344");
}

.hv7h32bkd {
  cx: 13.515px;
  cy: 10.008px;
  rx: 0.39px;
  ry: 0.197px;
}

.hwblgdbjb {
  d: path("M20.796 12.31a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.218");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i1-ophxps {
  d: path("M10.324 21.93v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i8-v2xbel {
  d: path("M11.157 21.543c0-.384.311-.696.695-.696h9.812v1.39h-9.812a.695.695 0 0 1-.695-.694");
}

.ijm85hble {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.586 10.339l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jws7bwb2s {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.11 10.131c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.073.368c.269.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.08-.45");
}

.k_e-s8buu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.078 4.158c.023.243.234 1.157.544 1.71");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kj_445bvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 28.62h1.922");
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kp9-98bbr {
  fill: var(--svg-color--000, #000);
  d: path("M14.296 10.519a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.236");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lb6_n4jos {
  stop-color: var(--svg-color--e3b388, #E3B388);
  stop-opacity: 0;
}

.lf-bul-6p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.228 4.444h26.213a.1.1 0 0 1 .1.1v19.584");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ljsj1x_ip {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.57 13.223c.405.215.886.339 1.399.339c.518 0 .994-.124 1.398-.34a.205.205 0 0 1 .247.042c.059.062.08.16.021.25m-3.064-.291l3.022.263m-3.022-.263a.205.205 0 0 0-.248.043a.196.196 0 0 0-.02.248m.268-.291l-.227.263m3.292.027l-.043-.027m.043.027l-.043-.027m.043.027a1.982 1.982 0 0 1-3.334 0m3.291-.027a1.932 1.932 0 0 1-3.249 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.miy6sr-xa {
  cx: 13.515px;
  cy: 10.008px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n5ywlebli {
  d: path("M13.353 25.42a.81.81 0 0 1-.302.667c.178.133.302.37.302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636c.187.144.302.39.302.668c-.009.42-.32.75-.684.75H9.734c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nfzhu5bbl {
  d: path("M11.283 12.31a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.218");
}

.nibr25dfr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.827 10.131c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.27.218-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.o5hkefbwq {
  fill-rule: evenodd;
  d: path("M23.154 12.11a3.25 3.25 0 0 0 .324-1.427c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.456.233l-.085.001A3.3 3.3 0 0 0 9.532 7.08v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.203.425-.324.9-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.122-.982-.324-1.407a.52.52 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.123 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.ob12b5chv {
  d: path("M20.844 8.698h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.omd21jb4q {
  stop-color: var(--svg-color--e8b8a6, #E8B8A6);
}

.os-6q6bjn {
  d: path("M21.664 23.035v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .753.61 1.363 1.363 1.363z");
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.oup8n6dpm {
  stop-color: var(--svg-color--d9a893, #D9A893);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p33iqucaj {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.418 30.05v-8.406h-2.094v8.406z");
}

.p5amjacbp {
  fill-rule: evenodd;
  d: path("M12.418 30.05v-8.406h-2.094v8.406z");
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmbuwrbwv {
  d: path("M29.004 24.04H3.014V5.05l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q_vkqua2e {
  d: path("M14.6 10.414c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q9z2zxzql {
  d: path("M20.796 11.774a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qu23eebor {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.908 8.328c.323-.079 1.125-.04 1.661.344");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyaeouklz {
  stop-color: var(--svg-color--eebea0, #EEBEA0);
  stop-opacity: 0;
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rl_kduowq {
  d: path("M11.302 11.774a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rxhwz8-zs {
  stop-color: var(--svg-color--885334, #885334);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s9f5xlzkg {
  stop-color: var(--svg-color--ab685c, #AB685C);
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.su97fabko {
  d: path("M16.014 15.55c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.svu_n61ll {
  d: path("M9.96 23.15c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tf_vtpbnm {
  d: path("M22.684 30.05V17.806a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.tic9i85fu {
  d: path("M11.075 4.686c.62-.553 1.517-.558 2.02-.47l.402 1.292c-.257-.04-.486.05-.68.234c-.452 1.676-2.162 1.425-2.497 2.682c-.15-1.492-.318-2.782.755-3.738");
}

.toq52_0ol {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 26.09h1.922");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uf-ge482b {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.087 9.815c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.uom77qk9x {
  fill: var(--svg-color--000, #000);
  d: path("M17.642 10.519a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.236");
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.uqw44xe1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 26.09H11.02");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va5jmqb6u {
  stop-color: var(--svg-color--bc8872, #BC8872);
}

.vgy50acyo {
  d: path("M9.304 30.05V17.806a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.vh6yi_hgr {
  stop-color: var(--svg-color--e4b392, #E4B392);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vvq7hbbzt {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wc5i2do8i {
  d: path("M22.057 23.158c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wledphbfk {
  d: path("M18.153 9.626a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.ww-u-6o5x {
  d: path("M29.384 25.04H2.634c-.34 0-.62-.28-.62-.62V4.67c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.x_eyyzgvq {
  stop-color: var(--svg-color--daa594, #DAA594);
  stop-opacity: 0;
}

.x109hm4su {
  stop-color: var(--svg-color--a66d4a, #A66D4A);
}

.x11m1v6la {
  d: path("M15.365 2.91c-1.132-.25-2.346.955-2.463 1.374c1.542 3.62 3.91 3.275 6.536 2.983c1.573-.174 1.744.542 1.878.889c-.436-4.056-3.37-4.677-5.95-5.246");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x8kkqybjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 27.355h1.922");
}

.x8r2h-b0e {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.571 8.922l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.009-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.094.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xsm2r-b6f {
  d: path("m15.586 10.339l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.yajmx8bkt {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.36 9.354c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yo4qn9o0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.578 9.354c-.653 0-1.205.45-1.355 1.059c-.045.175.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zpn51dtjs {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.576 10.478l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zt-qvcc3y {
  d: path("M16.014 18.72c-1.14 0-2.06-.92-2.06-2.06V14.1c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.zts3u4f8u {
  d: path("M13.785 9.626a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.zw2whl-je {
  stop-color: var(--svg-color--c48b7e, #C48B7E);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
