<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibN7n0d)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iARGKye)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iNseejd)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iuQYLUc)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#iK3vK0c)"><path class="g11vnob-s"/></g><g filter="url(#iRa1mmg)"><path class="ytl8wkbiv"/></g><g filter="url(#iuuEa9c)"><path class="s99p66ikg"/></g><g filter="url(#iUw4F4b)"><path class="pv3dgeoha"/></g><g filter="url(#iYE3njI)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#igsvMpe)"><path fill="url(#ioitlCc)" class="oa3f9ve3k"/></g><path fill="url(#i5Ao9Gd)" class="oa3f9ve3k"/><path fill="url(#i8KfH3d)" class="oa3f9ve3k"/><path fill="url(#iEdEbnd)" class="oa3f9ve3k"/><path class="a_g2v1e7w"/><path fill="url(#i5syKFD)" class="burjw8bvx"/><path fill="url(#ix4g9SG)" class="burjw8bvx"/><path fill="url(#i83V28c)" class="burjw8bvx"/><path fill="url(#iJXRjGd)" class="burjw8bvx"/><path fill="url(#iHjBAxX)" class="burjw8bvx"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><g filter="url(#ivOmrfb)"><path fill="url(#iVQsxVd)" class="m0kz_y80u"/><path fill="url(#i1oqYKe)" class="m0kz_y80u"/><path fill="url(#i47ILGc)" class="m0kz_y80u"/></g><path fill="url(#iuP6NMd)" class="eayua2tob"/><path fill="url(#iDv7Hjb)" class="eayua2tob"/><g filter="url(#iKkIdxd)"><path class="tjj6q_nem"/><path fill="url(#i40CHhd)" class="b47wb-b1b"/><path fill="url(#iOc4Lne)" class="b47wb-b1b"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#itC8Jgb)" class="z30kudb-o"/><g filter="url(#iizHwdc)"><path class="nkr0e_-9b"/><path fill="url(#iciFMOe)" class="k-27-x9ja"/><path fill="url(#iwzkgkd)" class="k-27-x9ja"/></g><g filter="url(#iOSirsd)"><path class="m3bis1bwo"/></g><path fill="url(#izDs5hc)" class="xgq6w0b8s"/><g filter="url(#itYWlxe)"><path class="cw_gb7c9k"/><path fill="url(#iSGVMGe)" class="my24k1swc"/></g><path fill="url(#inrcRqb)" class="my24k1swc"/><path fill="url(#iEr62fd)" class="my24k1swc"/><path fill="url(#icTBtvb)" class="m9o60j3-s"/><path fill="url(#iU8dDfc)" class="m9o60j3-s"/><path fill="url(#iTOjr5j)" class="m9o60j3-s"/><path fill="url(#iTSrjze)" class="m9o60j3-s"/><path fill="url(#i0yjX3b)" class="m9o60j3-s"/><path fill="url(#iPzK2eN)" class="jic9bm_zi"/><path fill="url(#iW48eqY)" class="etoheswcu"/><path fill="url(#imluD1d)" class="etoheswcu"/><path fill="url(#iriV3Ld)" class="awncbfucr"/><path fill="url(#imImPTb)" class="awncbfucr"/><g filter="url(#iVMULnw)"><path fill="url(#iq0NRpc)" class="tfn0nwzti"/></g><path fill="url(#iCvLRMx)" class="tfn0nwzti"/><path fill="url(#iaaj2Ec)" class="tfn0nwzti"/><path fill="url(#iImV5ae)" class="tfn0nwzti"/><g filter="url(#iopjyKe)"><path class="bysoj5a5f"/></g><g filter="url(#iGBERMb)"><path fill="url(#iXHU1Xb)" class="cqw2vfb2q"/><path fill="url(#iB10BRc)" class="cqw2vfb2q"/><path fill="url(#i6kbRze)" class="cqw2vfb2q"/><path fill="url(#iGx7xae)" class="cqw2vfb2q"/></g><path fill="url(#iVtWlJb)" class="shu4dibxw"/><g filter="url(#iRZ6gPb)"><path fill="url(#iS7mWYf)" class="jhk6cib2c"/><path fill="url(#iEdLYJc)" class="jhk6cib2c"/><path fill="url(#iDR0Hkd)" class="jhk6cib2c"/><path fill="url(#iKGvtMc)" class="jhk6cib2c"/><path fill="url(#iviFgfb)" class="jhk6cib2c"/></g><g filter="url(#ibGwnhb)"><path class="vi8m29b-c"/></g><g filter="url(#i6udMlb)"><path class="oqnrp0b-a"/></g><g filter="url(#ixMNNoc)"><path fill="url(#i211fJc)" class="ixt41qtdu"/><path fill="url(#i1oxIcb)" class="ixt41qtdu"/></g><g filter="url(#iRvKjcZ)"><path fill="url(#iMczsHd)" class="hfspox4ez"/><path fill="url(#iPh2UOb)" class="hfspox4ez"/><path fill="url(#inFx6nd)" class="hfspox4ez"/><path fill="url(#iR32KWc)" class="hfspox4ez"/></g><path class="kg948wbsd"/><path fill="url(#itlNzob)" class="ak6dd4b2u"/><path class="spuywcb1j"/><g filter="url(#iukC5lb)"><path class="q3so3_b5m"/><path fill="url(#i0m41Zd)" class="s_w8e6blm"/></g><g filter="url(#ixRJEPb)"><path fill="url(#iU2JA8c)" class="zgcsvxtfc"/></g><path class="e9qq9nbbm"/><path fill="url(#iI3DDvc)" class="b53k7vpcm"/><path class="z51w95brw"/><g filter="url(#iOO7oJZ)"><path fill="url(#i09cDAb)" class="t0aw6zuht"/></g><g filter="url(#iGwAgys)"><ellipse transform="rotate(-27.914 14.962 7.606)" class="ppof1mbxy"/><ellipse fill="url(#ix8UGjd)" transform="rotate(-27.914 14.962 7.606)" class="emt1ozbwk"/></g><path fill="url(#iIgKdoc)" class="xszfv_ghz"/><path fill="url(#i7P3Vgb)" class="xszfv_ghz"/><path fill="url(#imqt0ub)" class="xszfv_ghz"/><path fill="url(#iz2Pu5d)" class="rlohx9bqt"/><path fill="url(#i5E82Yd)" class="rlohx9bqt"/><g filter="url(#icNZ7Ie)"><path class="p-q4hjxou"/></g><g filter="url(#ijsh65d)"><path class="d9axz7bye"/></g><g filter="url(#icaMsHd)"><path class="mw-50ccvr"/></g><g filter="url(#iGUMtDX)"><path class="sjz1bkjyw"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="i5syKFD" cx="0" cy="0" r="1" gradientTransform="rotate(-105.819 17.69 2.831)scale(4.87202 1.60555)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="ix4g9SG" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 3.125 -1.0965 .4715 17.1 19.904)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="sl-3t4bfx"/><stop offset="1" class="zeih87brn"/></radialGradient><radialGradient id="iJXRjGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.73437 .44794 -.04289 16.242 18.481)" gradientUnits="userSpaceOnUse"><stop class="c6dvfyb6s"/><stop offset="1" class="oz3_ipb8v"/></radialGradient><radialGradient id="iHjBAxX" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 2.82812 -.75946 -.05455 15.241 19.966)" gradientUnits="userSpaceOnUse"><stop class="xo-vurl-f"/><stop offset="1" class="un08nrbhl"/></radialGradient><radialGradient id="i47ILGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17187 2.9198 -.50904 -.02996 15.382 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="qw90o_byh"/><stop offset="1" class="ampfxn_6u"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iOc4Lne" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="lhl06-bha"/><stop offset="1" class="l473kpbea"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="itC8Jgb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.564 3.998 7.72)scale(.69215 .70844)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="qtbbj-y7w"/><stop offset="1" class="ocvnedcjc"/></radialGradient><radialGradient id="iciFMOe" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="y9drs-b-r"/><stop offset=".995" class="o-5xddb6x"/></radialGradient><radialGradient id="iwzkgkd" cx="0" cy="0" r="1" gradientTransform="rotate(119.914 -.645 10.001)scale(.98695 .40009)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="s2zpt4bdz"/><stop offset="1" class="iwjfcrbly"/></radialGradient><radialGradient id="iSGVMGe" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.875 -2.0833 .9722 21.944 8.247)" gradientUnits="userSpaceOnUse"><stop class="em3moybkz"/><stop offset="1" class="mtf4q5bqt"/></radialGradient><radialGradient id="inrcRqb" cx="0" cy="0" r="1" gradientTransform="matrix(.26644 -4.07813 1.3228 .08642 23.615 13.013)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="er1wy7bvb"/><stop offset="1" class="yv86un7fh"/></radialGradient><radialGradient id="iEr62fd" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 6.033 12.706)scale(.35113 2.04974)" gradientUnits="userSpaceOnUse"><stop class="km2h82bty"/><stop offset="1" class="en0ycmbdo"/></radialGradient><radialGradient id="iTOjr5j" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.709)" gradientUnits="userSpaceOnUse"><stop class="hq3hkib4c"/><stop offset="1" class="k_rioyb_p"/></radialGradient><radialGradient id="iTSrjze" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.146 8.847)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="ignt4ubkd"/><stop offset="1" class="hts433_5m"/></radialGradient><radialGradient id="i0yjX3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.67188 4.0767 0 18.1 15.544)" gradientUnits="userSpaceOnUse"><stop class="xnxf0re5w"/><stop offset="1" class="utdakeidf"/></radialGradient><radialGradient id="iPzK2eN" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="muaav7b6p"/><stop offset="1" class="mudxz8mau"/></radialGradient><radialGradient id="iW48eqY" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.867 11.539)scale(1.66404 1.97675)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="imluD1d" cx="0" cy="0" r="1" gradientTransform="rotate(53.901 .628 22.1)scale(.21636 .18381)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iriV3Ld" cx="0" cy="0" r="1" gradientTransform="rotate(71.234 .872 13.757)scale(1.80083 .81856)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="imImPTb" cx="0" cy="0" r="1" gradientTransform="matrix(.1384 .43342 -.3802 .1214 13.906 8.502)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iq0NRpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27198 0 0 -4.09496 17.248 8.045)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iCvLRMx" cx="0" cy="0" r="1" gradientTransform="matrix(-.63 4.28125 -3.56513 -.52461 16.679 6.56)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="h6z9n3lki"/><stop offset="1" class="lhdcztxab"/></radialGradient><radialGradient id="iaaj2Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.61445 .73977 0 15.12 7.532)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iImV5ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6672 .86538 0 17.11 7.353)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iVtWlJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31323 1.26019 0 16.028 9.583)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iEdLYJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.48541 4.40366 0 13.756 7.358)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iDR0Hkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57872 2.79718 0 18.14 7.358)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iKGvtMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78466 -.62617 .33347 -.95045 17.813 4.63)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iviFgfb" cx="0" cy="0" r="1" gradientTransform="matrix(.39336 .64102 -1.4843 .91082 15.635 3.938)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="i211fJc" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.67 3.694)scale(1.75885 .48953)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="i1oxIcb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.852 -9.083)scale(2.61911 2.90171)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iMczsHd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47143 .34803 -.19464 .82293 17.602 5.07)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iPh2UOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.93377 -1.6096 .89766 -.52075 18.257 7.07)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="inFx6nd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 10.97 -1.65)scale(1.11304 .79722)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iR32KWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08536 .5003 -.54085 -2.25435 18.111 5.018)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="itlNzob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3526 -.56084 0 16.977 7.647)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0m41Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10079 -.12988 .17881 -.13876 16.878 7.684)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iI3DDvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35261 -.56087 0 15.08 7.647)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ix8UGjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21472 .2581 -.00404 14.955 7.742)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7P3Vgb" cx="0" cy="0" r="1" gradientTransform="matrix(.27316 .9749 -.93014 .26062 18.035 7.653)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="imqt0ub" cx="0" cy="0" r="1" gradientTransform="matrix(.34236 -.46984 .39382 .28697 18.192 7.89)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i5E82Yd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 3.7 9.502)scale(.91989 .90434)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="ibN7n0d" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1141" result="effect2_innerShadow_4002_1141"/></filter><filter id="iARGKye" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1141" result="effect2_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1141" result="effect3_innerShadow_4002_1141"/></filter><filter id="iNseejd" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1141" result="effect2_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1141" result="effect3_innerShadow_4002_1141"/></filter><filter id="iuQYLUc" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="iK3vK0c" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1141" result="effect2_dropShadow_4002_1141"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1141" result="shape"/></filter><filter id="iRa1mmg" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1141" result="effect2_dropShadow_4002_1141"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1141" result="shape"/></filter><filter id="iuuEa9c" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1141" result="effect2_dropShadow_4002_1141"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1141" result="shape"/></filter><filter id="iUw4F4b" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1141" result="effect2_dropShadow_4002_1141"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1141" result="shape"/></filter><filter id="iYE3njI" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="igsvMpe" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="ivOmrfb" width="2.97" height="8.306" x="13.261" y="21.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="iKkIdxd" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.576471 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="iizHwdc" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.564706 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.423529 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1141" result="effect2_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.619608 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1141" result="effect3_innerShadow_4002_1141"/></filter><filter id="iOSirsd" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="itYWlxe" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.556863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="iVMULnw" width="4.592" height="5.364" x="13.828" y="5.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="iopjyKe" width="2.816" height="3.26" x="14.53" y="6.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".5"/></filter><filter id="iGBERMb" width="1.016" height="1.46" x="15.52" y="7.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="iRZ6gPb" width="5.594" height="3.914" x="13.231" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1141" result="effect2_innerShadow_4002_1141"/></filter><filter id="ibGwnhb" width="1.073" height=".63" x="16.719" y="6.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="i6udMlb" width="1.073" height=".624" x="14.435" y="6.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1141"/></filter><filter id="ixMNNoc" width="2.844" height="2.565" x="13.394" y="4.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="iRvKjcZ" width="2.729" height="2.457" x="15.986" y="4.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="iukC5lb" width=".455" height=".416" x="16.601" y="7.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="ixRJEPb" width=".613" height=".623" x="16.909" y="7.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".1"/></filter><filter id="iOO7oJZ" width=".655" height=".678" x="14.979" y="7.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".1"/></filter><filter id="iGwAgys" width=".51" height=".419" x="14.707" y="7.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="icNZ7Ie" width=".66" height="1.117" x="13.365" y="7.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".075"/></filter><filter id="ijsh65d" width=".711" height="1.127" x="18.035" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".075"/></filter><filter id="icaMsHd" width="1.019" height=".478" x="14.412" y="6.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><filter id="iGUMtDX" width="1.019" height=".478" x="16.707" y="6.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1141" stdDeviation=".05"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i83V28c" x1="13.263" x2="14.851" y1="19.357" y2="19.357" gradientUnits="userSpaceOnUse"><stop class="x36zqabyv"/><stop offset="1" class="uktlcdafx"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iVQsxVd" x1="15.288" x2="12.882" y1="25.263" y2="25.294" gradientUnits="userSpaceOnUse"><stop offset=".113" class="dwuisxbps"/><stop offset="1" class="jot7ajumx"/></linearGradient><linearGradient id="i1oqYKe" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="xnu-7l9ks"/><stop offset="1" class="a4yl9qxqh"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="i40CHhd" x1="18.757" x2="18.351" y1="24.364" y2="24.091" gradientUnits="userSpaceOnUse"><stop offset=".202" class="o74y7ni4m"/><stop offset="1" class="c_2-erh-s"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="izDs5hc" x1="8.209" x2="7.425" y1="14.716" y2="15.269" gradientUnits="userSpaceOnUse"><stop offset=".337" class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="icTBtvb" x1="16.029" x2="16.029" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="ctgol8ben"/><stop offset="1" class="d2j7ihp4i"/></linearGradient><linearGradient id="iU8dDfc" x1="13.267" x2="15.457" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop offset=".01" class="k4svfjbzs"/><stop offset="1" class="k0oa_8bou"/></linearGradient><linearGradient id="iXHU1Xb" x1="16.028" x2="16.4" y1="8.406" y2="8.406" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iB10BRc" x1="15.562" x2="16.029" y1="8.338" y2="8.364" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="i6kbRze" x1="16.028" x2="16.028" y1="8.579" y2="8.949" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iGx7xae" x1="16.028" x2="16.028" y1="7.602" y2="7.784" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iS7mWYf" x1="18.359" x2="13.96" y1="5.584" y2="5.584" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iU2JA8c" x1="17.315" x2="17.178" y1="7.671" y2="7.755" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i09cDAb" x1="15.403" x2="15.267" y1="7.671" y2="7.755" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIgKdoc" x1="18.825" x2="18.301" y1="7.682" y2="8.628" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iz2Pu5d" x1="13.486" x2="14.12" y1="7.988" y2="7.933" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-fairy" /></template>
<style>
.a_g2v1e7w {
  fill: var(--svg-color--fb652d, #FB652D);
  d: path("M13.263 21.733V16.26l5.529.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.a4yl9qxqh {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ak6dd4b2u {
  d: path("M16.978 7.44a.388.388 0 0 1 .373.49h-.749a.39.39 0 0 1 .375-.49");
}

.ampfxn_6u {
  stop-color: var(--svg-color--e9af19, #E9AF19);
  stop-opacity: 0;
}

.awncbfucr {
  d: path("M13.916 8.589a.7.7 0 0 1-.393-.135v.405c0 .388.23.734.582.878a1.8 1.8 0 0 1-.15-.513z");
}

.b47wb-b1b {
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b53k7vpcm {
  d: path("M15.079 7.44a.388.388 0 0 0-.374.49h.75a.39.39 0 0 0-.376-.49");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.burjw8bvx {
  d: path("M13.263 21.733V16.26l5.529.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.bysoj5a5f {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.817 7.82l-.276.799c-.047.164.066.328.226.328h.342c.16 0 .273-.166.226-.328l-.23-.8c-.05-.176-.236-.176-.288 0");
}

.c_2-erh-s {
  stop-color: var(--svg-color--ffc93f, #FFC93F);
  stop-opacity: 0;
}

.c6dvfyb6s {
  stop-color: var(--svg-color--e94a61, #E94A61);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cqw2vfb2q {
  d: path("m15.862 7.735l-.23.799c-.048.164.065.328.225.328h.342c.16 0 .274-.166.226-.328l-.23-.8a.171.171 0 0 0-.333 0");
}

.ctgol8ben {
  stop-color: var(--svg-color--ff8328, #FF8328);
}

.cw_gb7c9k {
  fill: var(--svg-color--ffda42, #FFDA42);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.d2j7ihp4i {
  stop-color: var(--svg-color--ff712e, #FF712E);
}

.d9axz7bye {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M18.185 8.345q.025-.413.048-.827a.415.415 0 0 1-.048.827");
}

.dwuisxbps {
  stop-color: var(--svg-color--ffd240, #FFD240);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.e9qq9nbbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.99 7.322a.61.61 0 0 0-.59.46a.12.12 0 0 0 .117.148h.97a.1.1 0 0 0 .098-.118a.61.61 0 0 0-.596-.49");
}

.eayua2tob {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.em3moybkz {
  stop-color: var(--svg-color--f2b336, #F2B336);
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.emt1ozbwk {
  cx: 14.962px;
  cy: 7.606px;
  rx: 0.169px;
  ry: 0.086px;
}

.en0ycmbdo {
  stop-color: var(--svg-color--f2b133, #F2B133);
  stop-opacity: 0;
}

.er1wy7bvb {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.etoheswcu {
  d: path("M18.14 8.589a.7.7 0 0 0 .394-.135v.405a.94.94 0 0 1-.583.878q.112-.238.15-.513z");
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.ft5dv1b6b {
  fill: none;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h6z9n3lki {
  stop-color: var(--svg-color--f29540, #F29540);
  stop-opacity: 0;
}

.hfspox4ez {
  d: path("m18.294 7.07l-.013-.274a.64.64 0 0 0-.61-.62h-.61c-.386 0-.738-.21-.922-.547l-.02-.05c-.163-.474.31-.854.8-.748c.393.085.823.222 1.148.434c.758.494.626 1.386.227 1.805");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hq3hkib4c {
  stop-color: var(--svg-color--e0521f, #E0521F);
}

.hts433_5m {
  stop-color: var(--svg-color--ff9842, #FF9842);
  stop-opacity: 0;
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ignt4ubkd {
  stop-color: var(--svg-color--ff9842, #FF9842);
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.iwjfcrbly {
  stop-color: var(--svg-color--d08154, #D08154);
  stop-opacity: 0;
}

.ixt41qtdu {
  d: path("m16.13 5.605l-.03-.06a.29.29 0 0 0-.267-.181h-.553a1.46 1.46 0 0 0-1.452 1.468v.12c-.148-.113-.334-.35-.334-.734c0-.466.34-.701.557-.851c.06-.043.112-.078.143-.11l.044-.046c.152-.161.422-.448.895-.574q.099-.025.198-.041c.467-.076.807.343.807.816V5.6z");
}

.jhk6cib2c {
  d: path("M18.138 5.158a1.03 1.03 0 0 1 .505 1.555a.7.7 0 0 0-.117.38v.516a.8.8 0 0 0-.29-.116l.034-.698a.63.63 0 0 0-.6-.623h-.608c-.415 0-.79-.244-.961-.627a.29.29 0 0 0-.268-.181h-.553a1.46 1.46 0 0 0-1.452 1.468l.013.668a.74.74 0 0 0-.313.115v-.522a.7.7 0 0 0-.117-.38a1.04 1.04 0 0 1-.062-1.063c.126-.24.331-.408.564-.49a1.16 1.16 0 0 0 .602-.482a1.01 1.01 0 0 1 1.256-.396a.65.65 0 0 0 .519 0a1.01 1.01 0 0 1 1.26.41c.134.222.344.383.588.466");
}

.jic9bm_zi {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.35z");
}

.jot7ajumx {
  stop-color: var(--svg-color--f6ae2e, #F6AE2E);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k_rioyb_p {
  stop-color: var(--svg-color--e0521f, #E0521F);
  stop-opacity: 0;
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k0oa_8bou {
  stop-color: var(--svg-color--f36b26, #F36B26);
  stop-opacity: 0;
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k4svfjbzs {
  stop-color: var(--svg-color--d35c1b, #D35C1B);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kg948wbsd {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.067 7.322c.284 0 .524.195.59.46a.12.12 0 0 1-.117.148h-.97a.1.1 0 0 1-.099-.118c.055-.279.3-.49.596-.49");
}

.km2h82bty {
  stop-color: var(--svg-color--f2b133, #F2B133);
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
}

.l473kpbea {
  stop-color: var(--svg-color--ffe447, #FFE447);
  stop-opacity: 0;
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhdcztxab {
  stop-color: var(--svg-color--f29540, #F29540);
}

.lhl06-bha {
  stop-color: var(--svg-color--ffe447, #FFE447);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m0kz_y80u {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.438 7.053a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.m3bis1bwo {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m9o60j3-s {
  d: path("M16.016 10.71c-.437.014-1.419.083-1.984.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.765-.992a24 24 0 0 0-1.984-.163h-.027");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mtf4q5bqt {
  stop-color: var(--svg-color--f2b336, #F2B336);
  stop-opacity: 0;
}

.muaav7b6p {
  stop-color: var(--svg-color--f79d25, #F79D25);
}

.mudxz8mau {
  stop-color: var(--svg-color--ffbe35, #FFBE35);
}

.mw-50ccvr {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.562 6.825c.112-.08.39-.222.72-.166");
}

.my24k1swc {
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nkr0e_-9b {
  fill: var(--svg-color--ffc337, #FFC337);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o74y7ni4m {
  stop-color: var(--svg-color--f4c04c, #F4C04C);
}

.oa3f9ve3k {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.413.896a.22.22 0 0 0 .175.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.864-.459a.22.22 0 0 0-.206 0l-.87.462a.22.22 0 0 1-.32-.235l.178-.932a.22.22 0 0 0-.062-.198l-.727-.718a.22.22 0 0 1 .13-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.ocvnedcjc {
  stop-color: var(--svg-color--d59d43, #D59D43);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqnrp0b-a {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M14.546 6.703a1.2 1.2 0 0 1 .756-.156a.12.12 0 0 1-.03.239a.97.97 0 0 0-.635.145l-.007.005h-.001a.12.12 0 0 1-.148-.19z");
}

.oz3_ipb8v {
  stop-color: var(--svg-color--e94a61, #E94A61);
  stop-opacity: 0;
}

.p-q4hjxou {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M13.84 7.525a.415.415 0 0 0 .035.817a34 34 0 0 1-.036-.817");
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.ppof1mbxy {
  cx: 14.962px;
  cy: 7.606px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q3so3_b5m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.949 7.522c.028.037-.03.082-.096.13c-.066.05-.114.085-.142.048s.003-.107.069-.156c.066-.05.141-.06.169-.022");
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qtbbj-y7w {
  stop-color: var(--svg-color--cb8139, #CB8139);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw90o_byh {
  stop-color: var(--svg-color--bc8531, #BC8531);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rlohx9bqt {
  d: path("M13.832 7.238a.7.7 0 0 0 .06 1.39a34 34 0 0 1-.06-1.39");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_w8e6blm {
  d: path("M16.949 7.522c.028.037-.03.082-.096.13c-.066.05-.114.085-.142.048s.003-.107.069-.156c.066-.05.141-.06.169-.022");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s2zpt4bdz {
  stop-color: var(--svg-color--d08154, #D08154);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s99p66ikg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.shu4dibxw {
  d: path("M16.028 9.304c-.22 0-.428-.052-.602-.143c-.06-.03-.123.037-.086.091c.146.22.4.368.688.368a.82.82 0 0 0 .688-.368c.038-.056-.026-.12-.086-.09a1.3 1.3 0 0 1-.602.142");
}

.sjz1bkjyw {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.576 6.804a1 1 0 0 0-.72-.165");
}

.sl-3t4bfx {
  stop-color: var(--svg-color--e43423, #E43423);
}

.spuywcb1j {
  fill: var(--svg-color--000, #000);
  d: path("M16.755 7.828c0-.124.1-.222.223-.222a.22.22 0 0 1 .197.324h-.393a.2.2 0 0 1-.027-.102");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.t0aw6zuht {
  d: path("M15.434 7.782c0-.125-.102-.209-.13-.234l-.125.121l.077.157z");
}

.tfn0nwzti {
  d: path("M13.931 9.247c.112.848.834 1.48 1.69 1.48h.819c.855 0 1.577-.632 1.689-1.48c.051-.819.102-1.634.14-2.452a.63.63 0 0 0-.599-.623h-.608c-.415 0-.79-.244-.961-.627a.29.29 0 0 0-.268-.181h-.553a1.46 1.46 0 0 0-1.452 1.468c0 .809.05 1.604.103 2.415");
}

.tjj6q_nem {
  fill: var(--svg-color--ffc93e, #FFC93E);
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uin7i86hm {
  stop-color: var(--svg-color--ffc337, #FFC337);
}

.uktlcdafx {
  stop-color: var(--svg-color--dd4920, #DD4920);
  stop-opacity: 0;
}

.un08nrbhl {
  stop-color: var(--svg-color--ff6737, #FF6737);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utdakeidf {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vi8m29b-c {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M17.65 6.75a.8.8 0 0 0-.298-.178c-.132-.042-.298-.053-.527-.025a.12.12 0 1 0 .03.24c.208-.026.336-.013.424.015a.6.6 0 0 1 .213.13a.12.12 0 1 0 .159-.182");
}

.vj70_lxns {
  stop-color: var(--svg-color--ffc337, #FFC337);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x36zqabyv {
  stop-color: var(--svg-color--c45538, #C45538);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xgq6w0b8s {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xnu-7l9ks {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
}

.xnxf0re5w {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
}

.xo-vurl-f {
  stop-color: var(--svg-color--ff6737, #FF6737);
}

.xszfv_ghz {
  d: path("M18.167 8.628q.044-.693.08-1.387a.7.7 0 0 1-.08 1.387");
}

.y9drs-b-r {
  stop-color: var(--svg-color--e79b27, #E79B27);
  stop-opacity: 0;
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yv86un7fh {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
  stop-opacity: 0;
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z51w95brw {
  fill: var(--svg-color--000, #000);
  d: path("M15.301 7.828a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.393a.2.2 0 0 0 .026-.102");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zeih87brn {
  stop-color: var(--svg-color--e43423, #E43423);
  stop-opacity: 0;
}

.zgcsvxtfc {
  d: path("M17.323 7.777a.37.37 0 0 0-.1-.201l-.114.124l.051.099z");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
