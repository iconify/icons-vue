<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQsTqrc)"><path fill="url(#iImQ3ud)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#ijFub4b)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#iVMU9Bd)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#iVpizCe)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#iL0Xifb)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#izWm5GJ)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#i3a3Bib)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#idYHjCb)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#iFDB7Xd)" clip-rule="evenodd" class="bw2ygfbyo"/><path fill="url(#ixNOyJb)" clip-rule="evenodd" class="bw2ygfbyo"/></g><path fill="url(#iw27Ond)" class="xqv_7-bol"/><path fill="url(#i0sdxub)" class="i7luvbbid"/><path fill="url(#ihnoPwp)" class="i7luvbbid"/><path fill="url(#iLZkvez)" class="qm2t5tb6o"/><path fill="url(#ipyIOtc)" class="qm2t5tb6o"/><path fill="url(#iY2TIpd)" class="qm2t5tb6o"/><path fill="url(#ibBujLc)" class="qm2t5tb6o"/><path fill="url(#ieE9aDd)" class="bnsdedcnv"/><path fill="url(#itGyawb)" class="bnsdedcnv"/><path fill="url(#iIRXHtb)" class="bnsdedcnv"/><path fill="url(#imF2DDb)" class="bnsdedcnv"/><g filter="url(#i4CrFgc)"><path fill="url(#i4ZAMdb)" class="izhrvfbqo"/></g><g filter="url(#ibR9IXc)"><path fill="url(#iDgOI7d)" class="dzcrwjbzn"/></g><g filter="url(#iqPTTYc)"><path fill="url(#ikbKzzb)" class="unq8v8-sv"/></g><path fill="url(#ikYKsdp)" class="bejrr2btl"/><path fill="url(#i5slPpd)" class="bejrr2btl"/><path fill="url(#iQzqBac)" class="bejrr2btl"/><path fill="url(#iZFeA7b)" class="bejrr2btl"/><path fill="url(#i9eyFPd)" class="bejrr2btl"/><path fill="url(#ieoWp2b)" class="n9s70feqe"/><path fill="url(#iC10mcc)" class="n9s70feqe"/><path fill="url(#ivQ5N1c)" class="n9s70feqe"/><path fill="url(#ilVIQZc)" class="n9s70feqe"/><path fill="url(#iUUGcAd)" class="dzcrwjbzn"/><path fill="url(#iVlRZOb)" class="vk0144b-z"/><path fill="url(#i9hWCwd)" class="vk0144b-z"/><path fill="url(#iw27Ond)" class="xqv_7-bol"/><path fill="url(#i8mqxre)" class="uw1pkvzbq"/><path fill="url(#ikleYgP)" class="uw1pkvzbq"/><path fill="url(#igChqcN)" class="erbdqjbrn"/><path fill="url(#i6JuLkc)" class="erbdqjbrn"/><path fill="url(#idwDrKd)" class="qkhcoebdl"/><path fill="url(#iI0MsGe)" class="qkhcoebdl"/><path fill="url(#iYkWIqb)" class="qkhcoebdl"/><g filter="url(#iXWuFOd)"><rect class="w5a6b0bgs"/><rect fill="url(#i0E6Doc)" class="h4-anmblp"/><rect fill="url(#ib8OPDF)" class="h4-anmblp"/><rect fill="url(#iUjJd9W)" class="h4-anmblp"/></g><path fill="url(#iHuSWeb)" class="g24wfabgw"/><path fill="url(#irze7Me)" class="g24wfabgw"/><path fill="url(#iiE53kb)" class="g24wfabgw"/><path fill="url(#itV6SVv)" class="g24wfabgw"/><path fill="url(#iBQEMWX)" class="muzfdkb3s"/><path fill="url(#iPQIqwb)" class="lykr1opgf"/><g filter="url(#ifWvRGb)"><path fill="url(#idMgirv)" class="t8rtvxual"/><path fill="url(#iu5WRZd)" class="t8rtvxual"/><path fill="url(#i65uKre)" class="t8rtvxual"/><path fill="url(#i0tE27b)" class="t8rtvxual"/><path fill="url(#i6gx2Yb)" class="t8rtvxual"/></g><path fill="url(#iHmVQGb)" class="t8rtvxual"/><g filter="url(#iJEItBd)"><path stroke="url(#ivLhpkc)" class="ddtax3bkc"/></g><g filter="url(#izFgT2c)"><path stroke="url(#ivSX79c)" class="e1n6rrbnx"/></g><g filter="url(#iHDnUxc)"><path stroke="url(#iHeTaie)" class="ga8-0zb_z"/></g><path fill="url(#iaRVOeb)" class="f1ufwlsps"/><path fill="url(#iQ3bv6c)" class="q-pqg8bnx"/><g filter="url(#iyOrpee)"><path fill="url(#iXroO0c)" class="mlnnbfbfr"/></g><g filter="url(#ikEuRge)"><path fill="url(#iHsMAsd)" class="jl4y6u6ga"/><path fill="url(#iKg2Cac)" class="jl4y6u6ga"/></g><g filter="url(#icXhyse)"><path class="z7npr3b2i"/><path fill="url(#ihLO0ee)" class="lok0xxbxg"/></g><g filter="url(#iDlIU5b)"><path class="c8ia0xv0s"/><path fill="url(#i0YDfXb)" class="w-j_vcbix"/></g><g filter="url(#ihH8lZc)"><path fill="url(#igE86Ge)" class="eelqiwcti"/><path fill="url(#i8xlisd)" class="eelqiwcti"/><path fill="url(#i14CNvb)" class="eelqiwcti"/><path fill="url(#iKMH6TP)" class="eelqiwcti"/><path fill="url(#iXhHpLd)" class="eelqiwcti"/><path fill="url(#ivyjhbb)" class="eelqiwcti"/><path fill="url(#ilFhkEc)" class="eelqiwcti"/></g><path fill="url(#iaQ3aRb)" class="h06c8kqdp"/><path fill="url(#iK22xQb)" class="h06c8kqdp"/><g filter="url(#ickHIae)"><path class="uv3_hcbqq"/></g><g filter="url(#isb6rDd)"><path class="y60a33fiv"/><path fill="url(#idtCduc)" class="hxp9tabir"/><path fill="url(#iOdZPBb)" class="hxp9tabir"/><path fill="url(#iRrq0bG)" class="hxp9tabir"/></g><path fill="url(#iI2zSla)" class="hxp9tabir"/><path fill="url(#iaENvJc)" class="hxp9tabir"/><path stroke="url(#iqiTERb)" class="sx_2znbso"/><g filter="url(#iTO3Tjc)"><path class="g2s--_b6q"/></g><g filter="url(#iztn2QZ)"><path class="oqod90btj"/></g><g filter="url(#i85Vcqd)"><path class="ni--x40de"/></g><g filter="url(#iw3swVY)"><path clip-rule="evenodd" class="ik76_17it"/></g><path class="agpnjpbku"/><path fill="url(#iyTJoTb)" class="syl7-pbxl"/><path class="ol40sxbbw"/><g filter="url(#iOpbRVC)"><path class="ercusvbco"/><path fill="url(#iGxeX0c)" class="gxevu2owx"/></g><g filter="url(#ifp2kub)"><path fill="url(#iAP0qpe)" class="m8qkkfk-v"/></g><path class="ai882mbeg"/><path fill="url(#iy7OIcd)" class="ru9o2r3js"/><path class="d186aq3uk"/><g filter="url(#im0GWxd)"><path fill="url(#iIrUBYc)" class="y-f53tp_m"/></g><g filter="url(#iW1bSrd)"><ellipse transform="rotate(-27.914 12.972 9.892)" class="diaw87b9y"/><ellipse fill="url(#iaOk6id)" transform="rotate(-27.914 12.972 9.892)" class="jzwapccbq"/></g><g filter="url(#ipGAUxc)"><path class="n1rq3rbom"/></g><g filter="url(#i3bWywe)"><path class="azsfrmvpj"/></g><g filter="url(#iI3rdkd)"><path fill="url(#iSaVqkd)" class="sz93g977s"/><path fill="url(#iG1RolQ)" class="sz93g977s"/></g><g filter="url(#izYCz0d)"><path fill="url(#iDi9IAe)" class="b0ee45b0y"/><path fill="url(#iAjGAAd)" class="b0ee45b0y"/><path fill="url(#i3B8mfb)" class="b0ee45b0y"/></g><g filter="url(#izh6rUd)"><path stroke="url(#i9hVjgd)" class="agvv3ppzg"/></g><path fill="url(#iktUDAd)" class="buusmpjsz"/><g filter="url(#iymVeVd)"><path clip-rule="evenodd" class="ddmowvxiy"/></g><defs><radialGradient id="ijFub4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.119 16.404)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iVMU9Bd" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 2.98 11.43)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iVpizCe" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 3.866 8.786)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iL0Xifb" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.48 8.155)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="izWm5GJ" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.072 4.045)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="i3a3Bib" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 11.587 3.012)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="idYHjCb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.397 7.022)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iFDB7Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 22.935 9.733)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="ixNOyJb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 22.667 12.516)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="i0sdxub" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.272)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="do28bmb5k"/><stop offset="1" class="egj-02bls"/></radialGradient><radialGradient id="ihnoPwp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.272)" gradientUnits="userSpaceOnUse"><stop class="bfl4-fbqr"/><stop offset="1" class="frstvbc2m"/></radialGradient><radialGradient id="iLZkvez" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.496 14.539)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="ibBujLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.365)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="ieE9aDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.24)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="itGyawb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.49)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iDgOI7d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.865)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="ikYKsdp" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.647)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="i5slPpd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.272 -.277)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iQzqBac" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.253 14.358)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="ieoWp2b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.067)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="ivQ5N1c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.923)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iUUGcAd" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.797 11.8)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iVlRZOb" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.834)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="i8mqxre" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.522)" gradientUnits="userSpaceOnUse"><stop class="pplj5kbhg"/><stop offset=".632" class="m50akfb7d"/></radialGradient><radialGradient id="ikleYgP" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.884)" gradientUnits="userSpaceOnUse"><stop class="rdp66lkxf"/><stop offset="1" class="hvoveibaa"/></radialGradient><radialGradient id="igChqcN" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.576)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="i6JuLkc" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.421)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iYkWIqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.334)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="i0E6Doc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.022)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="ib8OPDF" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.004 18.872)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="iUjJd9W" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.233)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="itV6SVv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.178)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iu5WRZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.248)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i65uKre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.542)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i0tE27b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.792)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i6gx2Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.144)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iHmVQGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72856 5.10992 -3.29343 -1.7586 28.024 24.833)" gradientUnits="userSpaceOnUse"><stop class="hsdt12m1i"/><stop offset="1" class="v1bt46wqv"/></radialGradient><radialGradient id="iHsMAsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.465 11.024)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iKg2Cac" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 20.488 8.803)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ihLO0ee" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.24 -50.504)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i0YDfXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 10.76 10.585)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="igE86Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.285 10.047)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="i8xlisd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.326 10.745)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="i14CNvb" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.246 16.83)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iKMH6TP" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.02109 -9.51751 0 15.426 9.76)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="ndpka0b6p"/><stop offset="1" class="sq_t9kbem"/></radialGradient><radialGradient id="iXhHpLd" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.617 6.729)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ivyjhbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 17.727 9.629)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ilFhkEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 13.508 9.716)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iaQ3aRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 20.521 11.117)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iK22xQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 12.926 4.541)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="idtCduc" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.21 12.098)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iaENvJc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 5.975 8.388)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iyTJoTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.608 9.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iGxeX0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.38 10.072)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iy7OIcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.244 9.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iaOk6id" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.503 -1.274)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSaVqkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 9.468 4.336)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iG1RolQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 12.71 4.571)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iDi9IAe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.337 2.66)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iAjGAAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 17.739 3.834)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i3B8mfb" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.093 -.268)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><linearGradient id="iImQ3ud" x1="20.119" x2="13.314" y1="3.632" y2="16.237" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iw27Ond" x1="8.23" x2="22.659" y1="15.252" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ipyIOtc" x1="11.239" x2="11.239" y1="30.365" y2="29.053" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iY2TIpd" x1="15.177" x2="14.208" y1="29.053" y2="29.053" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iIRXHtb" x1="19.74" x2="19.74" y1="30.365" y2="29.053" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="imF2DDb" x1="15.802" x2="16.505" y1="27.928" y2="27.928" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="i4ZAMdb" x1="10.458" x2="12.677" y1="17.985" y2="24.672" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ikbKzzb" x1="20.633" x2="18.282" y1="19.035" y2="23.736" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iZFeA7b" x1="18.958" x2="17.552" y1="24.053" y2="22.553" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="i9eyFPd" x1="17.146" x2="17.974" y1="18.834" y2="19.178" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iC10mcc" x1="6.567" x2="6.567" y1="30.308" y2="29.174" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="ilVIQZc" x1="8.38" x2="7.935" y1="29.342" y2="29.339" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i9hWCwd" x1="22.753" x2="23.162" y1="27.615" y2="27.6" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="idwDrKd" x1="23.825" x2="26.529" y1="20.803" y2="20.803" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iI0MsGe" x1="26.529" x2="26.18" y1="20.787" y2="20.787" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="iHuSWeb" x1="26.529" x2="25.177" y1="23.115" y2="23.115" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="irze7Me" x1="26.529" x2="26.129" y1="23.264" y2="23.264" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iiE53kb" x1="23.696" x2="24.227" y1="23.264" y2="23.264" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="iBQEMWX" x1="24.782" x2="23.892" y1="21.756" y2="21.756" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iPQIqwb" x1="24.782" x2="23.892" y1="23.537" y2="23.537" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="idMgirv" x1="27.165" x2="23.137" y1="28.006" y2="28.006" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="ivLhpkc" x1="23.754" x2="25.463" y1="26.024" y2="26.024" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="ivSX79c" x1="23.676" x2="25.385" y1="27.328" y2="27.328" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iHeTaie" x1="23.754" x2="25.463" y1="28.633" y2="28.633" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iaRVOeb" x1="8.261" x2="22.637" y1="15.232" y2="15.232" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iQ3bv6c" x1="8.261" x2="22.637" y1="15.202" y2="15.202" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iXroO0c" x1="9.131" x2="12.09" y1="10.672" y2="10.672" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iOdZPBb" x1="14.379" x2="15.234" y1="12.116" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iRrq0bG" x1="15.426" x2="15.426" y1="12.97" y2="12.36" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iI2zSla" x1="15.504" x2="15.504" y1="12.944" y2="12.805" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iqiTERb" x1="14.697" x2="15.149" y1="14.192" y2="13.32" gradientUnits="userSpaceOnUse"><stop class="g9_0p3bal"/><stop offset="1" class="lu9o0bcgb"/></linearGradient><linearGradient id="iAP0qpe" x1="18.386" x2="18.072" y1="10.042" y2="10.235" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIrUBYc" x1="13.988" x2="13.674" y1="10.042" y2="10.235" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9hVjgd" x1="12.534" x2="13.079" y1="4.387" y2="5.661" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iktUDAd" x1="10.588" x2="22.177" y1="9.683" y2="9.683" gradientUnits="userSpaceOnUse"><stop class="aetlj_buy"/><stop offset=".115" class="yl8r25bpm"/><stop offset=".257" class="yl8r25bpm"/><stop offset=".917" class="pusr6ob-i"/></linearGradient><filter id="iQsTqrc" width="15.268" height="15.768" x="7.917" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="i4CrFgc" width="7.023" height="11.703" x="8.372" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".375"/></filter><filter id="ibR9IXc" width="5.673" height="10.453" x="9.475" y="15.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="iqPTTYc" width="6.388" height="10.529" x="15.682" y="16.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".375"/></filter><filter id="iXWuFOd" width="4.008" height=".781" x="23.173" y="18.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="ifWvRGb" width="4.468" height="5.556" x="23.137" y="24.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="iJEItBd" width="2.097" height=".3" x="23.604" y="25.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".05"/></filter><filter id="izFgT2c" width="2.097" height=".3" x="23.526" y="27.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".05"/></filter><filter id="iHDnUxc" width="2.097" height=".3" x="23.604" y="28.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".05"/></filter><filter id="iyOrpee" width="3.368" height="3.468" x="9.131" y="8.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="ikEuRge" width="3.218" height="3.468" x="18.644" y="8.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="icXhyse" width="3.148" height="3.148" x="18.679" y="9.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".25"/></filter><filter id="iDlIU5b" width="2.948" height="2.948" x="9.285" y="9.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".2"/></filter><filter id="ihH8lZc" width="10.191" height="11.127" x="10.33" y="5.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="ickHIae" width="2.877" height="3.682" x="13.825" y="9.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".25"/></filter><filter id="isb6rDd" width="2.377" height="3.182" x="14.237" y="9.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".125"/></filter><filter id="iTO3Tjc" width="3.001" height="1.285" x="16.368" y="9.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="iztn2QZ" width="3.001" height="1.285" x="11.482" y="9.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="i85Vcqd" width="2.453" height="1.091" x="11.618" y="7.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="iw3swVY" width="2.453" height="1.091" x="17.035" y="7.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/></filter><filter id="iOpbRVC" width=".787" height=".696" x="16.874" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".05"/></filter><filter id="ifp2kub" width=".891" height=".913" x="17.714" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".1"/></filter><filter id="im0GWxd" width=".986" height="1.04" x="13.271" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".1"/></filter><filter id="iW1bSrd" width=".913" height=".705" x="12.516" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".05"/></filter><filter id="ipGAUxc" width="2.661" height="1.378" x="16.865" y="7.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".2"/></filter><filter id="i3bWywe" width="2.661" height="1.378" x="11.414" y="7.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".2"/></filter><filter id="iI3rdkd" width="4.287" height="5.25" x="9.166" y="3.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".25"/></filter><filter id="izYCz0d" width="8.914" height="5.78" x="12.108" y="2.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".125"/></filter><filter id="izh6rUd" width="1.145" height="2.31" x="12.235" y="3.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2176" stdDeviation=".1"/></filter><filter id="iymVeVd" width="11.479" height="6.324" x="9.611" y="5.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.498039 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2176"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.741176 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2176" result="effect2_innerShadow_4002_2176"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-scientist-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.aetlj_buy {
  stop-color: var(--svg-color--9cc4ac, #9CC4AC);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.agpnjpbku {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.24c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.agvv3ppzg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.535 4.043c.023.243.234 1.157.544 1.71");
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.ai882mbeg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.24c-.653 0-1.205.45-1.355 1.058c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
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

.azsfrmvpj {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.574 8.212c-.322-.078-1.124-.039-1.66.345");
}

.b0ee45b0y {
  d: path("M14.822 2.794c-1.132-.25-2.346.956-2.463 1.375c1.542 3.62 3.91 3.275 6.536 2.983c1.573-.174 1.744.542 1.878.889c-.436-4.057-3.37-4.677-5.95-5.247");
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bejrr2btl {
  d: path("m21.37 17.067l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.249l.626.69a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803a10.6 10.6 0 0 1 2.61 1.255");
}

.bfl4-fbqr {
  stop-color: var(--svg-color--5f4786, #5F4786);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bnsdedcnv {
  d: path("M19.865 16.236a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.519z");
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.buusmpjsz {
  d: path("M18.083 6.42h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.278.533-.278.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.678a2.71 2.71 0 0 0-2.707-2.736");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.bw2ygfbyo {
  fill-rule: evenodd;
  d: path("M22.61 11.995c.213-.435.325-.921.325-1.427a3.3 3.3 0 0 0-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.011a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.454-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.213 3.3v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455M10.35 9.322h-.011l1.198 2.356c.123 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.462.051l-.082.194a2.3 2.3 0 0 1-1.24 1.255q-.027.012-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c8ia0xv0s {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.76 11.66a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d186aq3uk {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.403a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.ddmowvxiy {
  fill: var(--svg-color--9b94a2, #9B94A2);
  fill-rule: evenodd;
  d: path("M9.761 9.125c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.341c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.016zm.6.003a2.42 2.42 0 0 0 2.417 2.415c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34a.74.74 0 0 1 .609.34v.002a2.46 2.46 0 0 0 2.114 1.077c1.248-.045 2.31-1.134 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.ddtax3bkc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.945h1.797");
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.diaw87b9y {
  cx: 12.972px;
  cy: 9.892px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.do28bmb5k {
  stop-color: var(--svg-color--755b9f, #755B9F);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dzcrwjbzn {
  d: path("m9.608 17.067l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803a10.6 10.6 0 0 0-2.61 1.255");
}

.e1n6rrbnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.25h1.797");
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eelqiwcti {
  d: path("m10.34 9.057l-.01-.306c.02-.949.575-1.316.81-1.439l.052-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.egj-02bls {
  stop-color: var(--svg-color--482f73, #482F73);
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.erbdqjbrn {
  d: path("M26.434 22.913c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.ercusvbco {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.7c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.f1ufwlsps {
  d: path("M15.8 15.203c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.frstvbc2m {
  stop-color: var(--svg-color--5f4786, #5F4786);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g24wfabgw {
  d: path("M26.529 21.178v4.172h-2.704v-4.172z");
}

.g2s--_b6q {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.568 10.016c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.08-.45");
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g9_0p3bal {
  stop-color: var(--svg-color--d9a59c, #D9A59C);
}

.ga8-0zb_z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.555h1.797");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxevu2owx {
  d: path("M17.544 9.7c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h06c8kqdp {
  d: path("M10.339 9.322h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.h4-anmblp {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.631px;
  rx: 0.391px;
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hsdt12m1i {
  stop-color: var(--svg-color--feca9f, #FECA9F);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hvoveibaa {
  stop-color: var(--svg-color--cf8b7d, #CF8B7D);
  stop-opacity: 0;
}

.hxp9tabir {
  d: path("m15.044 10.479l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i7luvbbid {
  d: path("M15.466 15.303c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ik76_17it {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.157 8.35l-.137.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.094-.528c.514-.09.989 0 1.329.109a3.3 3.3 0 0 1 .558.239l.01.005z");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.izhrvfbqo {
  d: path("m9.255 17.764l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jl4y6u6ga {
  d: path("M20.253 12.194a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jzwapccbq {
  cx: 12.972px;
  cy: 9.892px;
  rx: 0.39px;
  ry: 0.197px;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lok0xxbxg {
  d: path("M20.253 11.66a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.lu9o0bcgb {
  stop-color: var(--svg-color--d9a59c, #D9A59C);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lykr1opgf {
  d: path("M23.825 23.772v-.47h.805a.234.234 0 1 1 0 .47z");
}

.m50akfb7d {
  stop-color: var(--svg-color--cf8f8d, #CF8F8D);
}

.m8qkkfk-v {
  d: path("M18.405 10.286a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mlnnbfbfr {
  d: path("M10.74 12.194a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.muzfdkb3s {
  d: path("M23.825 21.99v-.468h.805a.234.234 0 1 1 0 .468z");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n1rq3rbom {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.365 8.212c.323-.078 1.125-.039 1.661.345");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.n9s70feqe {
  d: path("M8.226 29.943v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.ndpka0b6p {
  stop-color: var(--svg-color--c7878b, #C7878B);
  stop-opacity: 0;
}

.ni--x40de {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.028 8.807l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.002-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol40sxbbw {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.403c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.oqod90btj {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.284 10.016c-.266-.467-.67-.835-1.538-.835c-.38 0-.746.105-1.072.368c-.27.218-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pplj5kbhg {
  stop-color: var(--svg-color--be7682, #BE7682);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pusr6ob-i {
  stop-color: var(--svg-color--97c1a5, #97C1A5);
  stop-opacity: 0.75;
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q-pqg8bnx {
  d: path("M15.47 15.203h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qkhcoebdl {
  d: path("M23.825 19.412h2.703v5.938h-2.703z");
}

.qm2t5tb6o {
  d: path("M11.114 16.236a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.519z");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rdp66lkxf {
  stop-color: var(--svg-color--cf8b7d, #CF8B7D);
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.ru9o2r3js {
  d: path("M13.242 9.51a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sq_t9kbem {
  stop-color: var(--svg-color--bd7689, #BD7689);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sx_2znbso {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.028 13.108a3 3 0 0 0 1.398.338c.518 0 .994-.123 1.398-.338a.205.205 0 0 1 .247.04c.058.063.08.161.021.25m-3.064-.29l3.022.263m-3.022-.263a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248m.268-.291l-.227.263m3.291.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.291-.027a1.932 1.932 0 0 1-3.249 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.syl7-pbxl {
  d: path("M17.61 9.51a.892.892 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .864-1.128");
}

.sz93g977s {
  d: path("M10.532 4.571c.62-.553 1.516-.559 2.02-.47l.402 1.291c-.258-.039-.487.05-.68.235c-.452 1.676-2.162 1.425-2.497 2.682c-.15-1.492-.318-2.783.755-3.738");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t8rtvxual {
  d: path("M23.137 25.269c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.unq8v8-sv {
  d: path("m21.202 18.207l.116 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.075.22l.554.611a.44.44 0 0 1-.013.608l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136a9.4 9.4 0 0 1 2.31 1.112");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uv3_hcbqq {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.033 10.618l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.uw1pkvzbq {
  d: path("M15.426 18.573a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v1bt46wqv {
  stop-color: var(--svg-color--feca9f, #FECA9F);
  stop-opacity: 0;
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vk0144b-z {
  d: path("M22.753 29.943v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w-j_vcbix {
  d: path("M10.76 11.66a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w5a6b0bgs {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.631px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xqv_7-bol {
  d: path("M15.466 15.253h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y-f53tp_m {
  d: path("M14.057 10.298c0-.288-.235-.48-.298-.538l-.288.279l.177.36z");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y60a33fiv {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.044 10.479l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yl8r25bpm {
  stop-color: var(--svg-color--77a78a, #77A78A);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z7npr3b2i {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.253 11.66a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
