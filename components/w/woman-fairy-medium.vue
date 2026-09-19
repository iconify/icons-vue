<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQLcHEk)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iUVVPdb)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iEoaTEe)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iSJavmk)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i6v6cYT)"><path class="er079sbvz"/></g><g filter="url(#i4PSDwb)"><path class="ytl8wkbiv"/></g><g filter="url(#iLnBQNd)"><path class="m8pucsqyt"/></g><g filter="url(#iWsTaze)"><path class="pv3dgeoha"/></g><g filter="url(#iztC7yv)"><path fill="url(#i2uqO5z)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#i62sQNc)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#iwXYJlb)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#iCGVnTP)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#i3jcBXb)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#iKkbfId)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#iLuJjbc)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#iAC5ksd)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#i6qSXwe)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#ih7N3eb)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#ix2exyb)" clip-rule="evenodd" class="e2ldg7xck"/><path fill="url(#ipP3wWc)" clip-rule="evenodd" class="e2ldg7xck"/></g><g filter="url(#i0v0cNe)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#iF4awKe)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="c_ir2fb_m"/><path fill="url(#i7QnpSd)" class="eahf9fbrk"/><path fill="url(#iJU4nte)" class="eahf9fbrk"/><path fill="url(#iNCrKDe)" class="j-tweow-u"/><path fill="url(#ipj49hY)" class="j-tweow-u"/><path fill="url(#iyc0UzP)" class="j-tweow-u"/><path fill="url(#iyo9zLW)" class="j-tweow-u"/><path fill="url(#iuP6NMd)" class="bm7w23b9t"/><path fill="url(#iDv7Hjb)" class="bm7w23b9t"/><g filter="url(#iHqAAEE)"><path class="mdab-tbej"/><path fill="url(#iQK8uac)" class="r7kas8b0r"/><path fill="url(#iayy3Lb)" class="r7kas8b0r"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#i2uH9Pc)" class="z30kudb-o"/><g filter="url(#ibcEGwM)"><path class="vnfh0zkir"/><path fill="url(#iQFMGZc)" class="uu9c01xwt"/><path fill="url(#im8X1Tc)" class="uu9c01xwt"/></g><g filter="url(#inRlWad)"><path class="ze31rdbyh"/></g><g filter="url(#ihqoMob)"><path class="vfl1x5hzz"/><path fill="url(#iOxJnic)" class="h2pt4jb3o"/><path fill="url(#izhnhRx)" class="h2pt4jb3o"/></g><g filter="url(#i2cayNd)"><path class="kahu9wb3l"/></g><path fill="url(#iWroyTd)" class="nrezcp5le"/><path fill="url(#izNTKdc)" class="nrezcp5le"/><path fill="url(#iiD6wCc)" class="nrezcp5le"/><path fill="url(#iKByDMe)" class="nrezcp5le"/><path fill="url(#iBJnkMe)" class="nrezcp5le"/><path fill="url(#ilgbsNb)" class="b6pcaeboe"/><g filter="url(#iuG8j8G)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#iRJZAwc)"><path stroke="url(#io1soLc)" class="iqsdfibon"/></g><path fill="url(#irGgnec)" class="f28zyusup"/><path fill="url(#iHeluSb)" class="ju-3ieb_x"/><g filter="url(#iJ50Bbb)"><path fill="url(#iGDJWhc)" class="ssyj8hboz"/></g><path fill="url(#i7J8LXb)" class="ssyj8hboz"/><g filter="url(#iQr8Mjb)"><path fill="url(#iDUDoFe)" class="vwxh7jegl"/><path fill="url(#iyrO9Lc)" class="vwxh7jegl"/></g><g filter="url(#i57KTpc)"><path class="t48-l2bco"/><path fill="url(#iuxmC1b)" class="yckxtx0he"/></g><g filter="url(#iH7MqJe)"><path class="vghwp6-5c"/><path fill="url(#ieDq6ke)" class="ei67qgb4y"/></g><g filter="url(#iFUssvy)"><path fill="url(#iDsOajc)" class="iy1tv409t"/><path fill="url(#iYQUSUd)" class="iy1tv409t"/><path fill="url(#ieN5T9d)" class="iy1tv409t"/><path fill="url(#i4GJhie)" class="iy1tv409t"/><path fill="url(#il5GIAe)" class="iy1tv409t"/><path fill="url(#iB5NLrd)" class="iy1tv409t"/><path fill="url(#iwj97Qd)" class="iy1tv409t"/><path fill="url(#itY9tie)" class="iy1tv409t"/></g><path fill="url(#ijnWRVb)" class="iy1tv409t"/><g filter="url(#iVKRcWW)"><path class="yiaq2oila"/></g><g filter="url(#i7WYzwe)"><path class="iuqnbtb8k"/><path fill="url(#i3ndQIs)" class="w7ma6l7fs"/><path fill="url(#i1q0ngb)" class="w7ma6l7fs"/><path fill="url(#ilrlNwd)" class="w7ma6l7fs"/><path fill="url(#ieRYihb)" class="w7ma6l7fs"/></g><g filter="url(#iVIBkfE)"><path stroke="url(#ipfgy0m)" class="yxx_q1b1a"/></g><path class="t8_yaabsm"/><g filter="url(#iLJtPub)"><path class="oxvn1x5xs"/></g><g filter="url(#iqB1j6d)"><path class="jop43d12t"/></g><g filter="url(#iTnoJkc)"><path class="prw3-ibql"/></g><g filter="url(#iMECgFe)"><path clip-rule="evenodd" class="sen0n_b0o"/></g><path class="xx5_pxj-t"/><path fill="url(#icdgn8c)" class="wzzru_b9g"/><path class="bq010tbbk"/><g filter="url(#iX8fOXb)"><path class="dtrv1ybfs"/><path fill="url(#i2oxXOd)" class="h25f5pelt"/></g><g filter="url(#iMF6ofd)"><path fill="url(#ipgkKTb)" class="dg7g-pbpg"/></g><path class="pom__eb7s"/><path fill="url(#iEr56Qb)" class="ue6n0w96y"/><path class="yozsjebeb"/><g filter="url(#ixT3gGc)"><path fill="url(#igEo7Ee)" class="trk0d3lvr"/></g><g filter="url(#ifubsMd)"><ellipse transform="rotate(-27.914 14.94 7.52)" class="tjku6kbhg"/><ellipse fill="url(#iKClBMd)" transform="rotate(-27.914 14.94 7.52)" class="zjxboub4f"/></g><g filter="url(#ikm00MY)"><path class="qmv39g7bi"/><path fill="url(#ijmu54d)" class="w83i6gbkm"/><path fill="url(#iU76OHe)" class="w83i6gbkm"/></g><g filter="url(#iCUrcMR)"><path class="m-5ct0byw"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="i62sQNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26788 2.0241 -2.5285 -.33463 15.894 8.939)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iwXYJlb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.938 6.767)scale(1.54385 2.0285)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iCGVnTP" cx="0" cy="0" r="1" gradientTransform="matrix(-.58043 .75904 -.58284 -.4457 13.878 7.926)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="i3jcBXb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 5.07 7.46)scale(1.09885 .77404)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iKkbfId" cx="0" cy="0" r="1" gradientTransform="matrix(.6102 1.16087 -1.61147 .84705 14.466 4.25)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iLuJjbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63993 .63997 -.89435 -.89429 18.618 5.172)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iAC5ksd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81853 .23813 -.4966 -1.70698 19.362 7.45)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i6qSXwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25013 .31255 -.39814 -1.59248 19.094 8.967)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="ih7N3eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40154 -1.17663 .93065 -.3176 18.13 6.369)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ix2exyb" cx="0" cy="0" r="1" gradientTransform="matrix(.6677 .07007 -.11353 1.08184 13.308 7.436)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ipP3wWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37207 -1.64458 .59356 -.13429 18.298 7.144)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iyc0UzP" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.7132 -.85217 -.06096 15.406 25.564)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="zedm4_93e"/><stop offset="1" class="p47p3ixdi"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iayy3Lb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="gg9v3ibhg"/><stop offset="1" class="jgrs-ob8h"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="i2uH9Pc" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="sduk0cbig"/><stop offset="1" class="ayl9o28ey"/></radialGradient><radialGradient id="iQFMGZc" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ygruuqhoq"/><stop offset="1" class="k1-hbtbhm"/></radialGradient><radialGradient id="im8X1Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="hmivjlemy"/><stop offset="1" class="z7rmu-ysc"/></radialGradient><radialGradient id="iOxJnic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="m554dhpjb"/><stop offset="1" class="chq9htb5s"/></radialGradient><radialGradient id="izhnhRx" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="k3eoh3x-c"/><stop offset="1" class="i6g4-tg4y"/></radialGradient><radialGradient id="iiD6wCc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="g7dj32byf"/><stop offset="1" class="mv_j9hb5m"/></radialGradient><radialGradient id="ilgbsNb" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 1.25508 -2.35578 1.02647 15.148 10.137)" gradientUnits="userSpaceOnUse"><stop class="vd43a7ybz"/><stop offset="1" class="rglphuhmg"/></radialGradient><radialGradient id="i7J8LXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29022 -.5343 .60543 -.32886 13.774 8.542)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iDUDoFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.10507 -.5023 .61329 1.34923 17.822 8.022)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iyrO9Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.53579 0 0 .23069 18.224 7.07)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iuxmC1b" cx="0" cy="0" r="1" gradientTransform="matrix(.67035 -.04986 .03898 .52402 17.978 7.877)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ieDq6ke" cx="0" cy="0" r="1" gradientTransform="rotate(180 6.993 3.913)scale(.46881)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iDsOajc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.816 5.692)scale(3.17959 4.25583)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iYQUSUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96798 .42594 -.29662 -.67408 16.903 7.968)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="ieN5T9d" cx="0" cy="0" r="1" gradientTransform="matrix(.57234 -1.74407 2.2129 .7262 15.068 10.478)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i4GJhie" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.40625 -4.25777 0 16.483 7.236)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="zlwhb3jwn"/><stop offset=".955" class="kt1b6lbfw"/></radialGradient><radialGradient id="il5GIAe" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.01 4.997)scale(3.12438 5.37922)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iB5NLrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5109 .62702 0 17.05 7.403)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iwj97Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58271 .66783 0 15.106 7.301)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="itY9tie" cx="0" cy="0" r="1" gradientTransform="matrix(-.38632 1.43257 -1.1463 -.30912 16.642 6.375)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ijnWRVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57063 0 0 -2.86163 18.29 8.063)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="i3ndQIs" cx="0" cy="0" r="1" gradientTransform="matrix(-.20225 -.90748 .27968 -.06233 16.377 8.386)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="ieRYihb" cx="0" cy="0" r="1" gradientTransform="matrix(-.34603 0 0 -.09674 16.27 8.48)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="icdgn8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3602 -.57294 0 16.997 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i2oxXOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10296 -.13268 .18267 -.14176 16.896 7.6)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEr56Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3602 -.57294 0 15.06 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKClBMd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.236 -3.52)scale(.21937 .2637)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijmu54d" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.084 7.46)scale(2.16342 3.53706)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iU76OHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.09338 .607 -1.30592 -.2009 16.122 4.473)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iQLcHEk" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1151" result="effect2_innerShadow_4002_1151"/></filter><filter id="iUVVPdb" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1151" result="effect2_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1151" result="effect3_innerShadow_4002_1151"/></filter><filter id="iEoaTEe" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1151" result="effect2_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1151" result="effect3_innerShadow_4002_1151"/></filter><filter id="iSJavmk" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="i6v6cYT" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1151" result="effect2_dropShadow_4002_1151"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1151" result="shape"/></filter><filter id="i4PSDwb" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1151" result="effect2_dropShadow_4002_1151"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1151" result="shape"/></filter><filter id="iLnBQNd" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1151" result="effect2_dropShadow_4002_1151"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1151" result="shape"/></filter><filter id="iWsTaze" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1151" result="effect2_dropShadow_4002_1151"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1151" result="shape"/></filter><filter id="iztC7yv" width="6.918" height="7.418" x="12.695" y="3.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="i0v0cNe" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iF4awKe" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iHqAAEE" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="ibcEGwM" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.392157 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.254902 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1151" result="effect2_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.443137 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1151" result="effect3_innerShadow_4002_1151"/></filter><filter id="inRlWad" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="ihqoMob" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.380392 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="i2cayNd" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.34902 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iuG8j8G" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1151" result="effect2_innerShadow_4002_1151"/></filter><filter id="iRJZAwc" width="4.609" height="5.161" x="18.951" y="9.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".25"/></filter><filter id="iJ50Bbb" width="1.579" height="1.429" x="13.234" y="7.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iQr8Mjb" width="1.429" height="1.679" x="17.457" y="6.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="i57KTpc" width="1.354" height="1.354" x="17.495" y="7.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".1"/></filter><filter id="iH7MqJe" width="1.354" height="1.354" x="13.28" y="7.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".1"/></filter><filter id="iFUssvy" width="4.524" height="4.879" x="13.766" y="5.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iVKRcWW" width="1.833" height="2.191" x="15.04" y="7.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".25"/></filter><filter id="i7WYzwe" width="1.033" height="1.391" x="15.512" y="7.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".05"/></filter><filter id="iVIBkfE" width="1.666" height=".7" x="15.195" y="8.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".025"/></filter><filter id="iLJtPub" width="1.444" height=".571" x="16.335" y="7.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iqB1j6d" width="1.444" height=".571" x="14.278" y="7.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iTnoJkc" width="1.2" height=".596" x="14.338" y="6.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iMECgFe" width="1.2" height=".596" x="16.743" y="6.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/></filter><filter id="iX8fOXb" width=".461" height=".42" x="16.616" y="7.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".05"/></filter><filter id="iMF6ofd" width=".618" height=".628" x="16.933" y="7.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".1"/></filter><filter id="ixT3gGc" width=".66" height=".684" x="14.96" y="7.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".1"/></filter><filter id="ifubsMd" width=".517" height=".424" x="14.681" y="7.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".05"/></filter><filter id="ikm00MY" width="4.048" height="2.645" x="14.454" y="4.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1151"/><feGaussianBlur result="effect2_foregroundBlur_4002_1151" stdDeviation=".05"/></filter><filter id="iCUrcMR" width="2.988" height="1.631" x="15.703" y="5.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1151" stdDeviation=".2"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i2uqO5z" x1="18.112" x2="15.388" y1="4.741" y2="9.518" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iNCrKDe" x1="15.345" x2="13.875" y1="24.348" y2="24.348" gradientUnits="userSpaceOnUse"><stop offset=".267" class="p_tr_bcwq"/><stop offset=".945" class="e4g-mccex"/></linearGradient><linearGradient id="ipj49hY" x1="15.517" x2="15.017" y1="26.036" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="qg92x2blu"/><stop offset="1" class="isygt5c6e"/></linearGradient><linearGradient id="iyo9zLW" x1="13.318" x2="13.75" y1="24.833" y2="24.833" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="iQK8uac" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="f_kjwkbbu"/><stop offset="1" class="f0f59mb_p"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="io1soLc" x1="22.451" x2="19.857" y1="11.683" y2="13.527" gradientUnits="userSpaceOnUse"><stop offset=".18" class="aex1w9h9c"/><stop offset="1" class="h5gnwgbqc"/></linearGradient><linearGradient id="irGgnec" x1="12.937" x2="19.259" y1="10.014" y2="10.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeluSb" x1="12.937" x2="19.259" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGDJWhc" x1="13.234" x2="14.058" y1="7.866" y2="7.866" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i1q0ngb" x1="15.612" x2="16.028" y1="8.418" y2="8.418" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="ilrlNwd" x1="16.028" x2="16.028" y1="8.732" y2="8.454" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ipfgy0m" x1="15.556" x2="15.76" y1="9.399" y2="9.083" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ipgkKTb" x1="17.343" x2="17.203" y1="7.586" y2="7.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igEo7Ee" x1="15.39" x2="15.251" y1="7.586" y2="7.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.aex1w9h9c {
  stop-color: var(--svg-color--b58c7d, #B58C7D);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.ayl9o28ey {
  stop-color: var(--svg-color--8f566c, #8F566C);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bm7w23b9t {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.bq010tbbk {
  fill: var(--svg-color--000, #000);
  d: path("M16.771 7.747c0-.126.1-.227.227-.227a.226.226 0 0 1 .202.331h-.402a.2.2 0 0 1-.027-.104");
}

.c_ir2fb_m {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.chq9htb5s {
  stop-color: var(--svg-color--bb9586, #BB9586);
  stop-opacity: 0;
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
}

.dg7g-pbpg {
  d: path("M17.35 7.695a.37.37 0 0 0-.102-.206l-.115.127l.052.101z");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dtrv1ybfs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.969 7.434c.028.038-.03.084-.098.134c-.067.05-.117.086-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2ldg7xck {
  fill-rule: evenodd;
  d: path("M19.218 8.453a1.45 1.45 0 0 0 .024-1.213h.003a1.4 1.4 0 0 0-.125-.228v-.001a1.44 1.44 0 0 1-.234-.786V6.22c0-.809-.656-1.465-1.465-1.465a.24.24 0 0 1-.202-.103a1.468 1.468 0 0 0-2.381 0a.25.25 0 0 1-.202.103h-.038A1.465 1.465 0 0 0 13.17 6.22v.005c0 .278-.081.552-.234.786v.002a1.47 1.47 0 0 0-.099 1.44a.23.23 0 0 1 0 .202a1.427 1.427 0 0 0 1.285 2.053h3.81a1.427 1.427 0 0 0 1.285-2.053a.23.23 0 0 1 0-.202m-5.443-1.186h-.005l.532 1.046c.055 1.244.54 0 1.726 0s1.704 1.384 1.758.14l.505-1.42c-.024-.552-.425-.59-.505-.59h-1.43a1.72 1.72 0 0 1-1.415-.744a.117.117 0 0 0-.205.023l-.037.086c-.1.25-.29.44-.528.548l-.022.01l-.023.008c-.105.055-.35.218-.36.64l.005.135z");
}

.e4g-mccex {
  stop-color: var(--svg-color--a77871, #A77871);
}

.eahf9fbrk {
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.ei67qgb4y {
  d: path("M13.957 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.er079sbvz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.f_kjwkbbu {
  stop-color: var(--svg-color--b38885, #B38885);
}

.f0f59mb_p {
  stop-color: var(--svg-color--bb8981, #BB8981);
  stop-opacity: 0;
}

.f28zyusup {
  d: path("M16.253 10.001q.166.009.338.022c-.114-.008-.224-.017-.338-.022");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g7dj32byf {
  stop-color: var(--svg-color--402d65, #402D65);
}

.gg9v3ibhg {
  stop-color: var(--svg-color--cda38f, #CDA38F);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h25f5pelt {
  d: path("M16.969 7.434c.028.038-.03.084-.098.134c-.067.05-.117.086-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.h2pt4jb3o {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.h5gnwgbqc {
  stop-color: var(--svg-color--c39b88, #C39B88);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hmivjlemy {
  stop-color: var(--svg-color--8a405c, #8A405C);
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i6g4-tg4y {
  stop-color: var(--svg-color--a77b6c, #A77B6C);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iqsdfibon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.701 12.745l2.672 1.045a.1.1 0 0 0 .136-.084l.302-3.57");
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.isygt5c6e {
  stop-color: var(--svg-color--af8375, #AF8375);
  stop-opacity: 0;
}

.iuqnbtb8k {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.859 7.667l-.236.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.287-.167-.34 0");
}

.iy1tv409t {
  d: path("M13.77 7.267h.005l-.004-.118l-.005-.136c.01-.421.255-.584.36-.639l.023-.009l.022-.009c.237-.109.428-.299.528-.548l.037-.086c.036-.086.15-.1.205-.023c.318.467.851.743 1.416.743h1.43c.08 0 .48.039.504.592l-.053 1.364c-.055 1.244-1.027 2.08-2.213 2.08s-2.157-.836-2.212-2.08z");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jgrs-ob8h {
  stop-color: var(--svg-color--cda38f, #CDA38F);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jop43d12t {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M15.521 7.575c-.118-.208-.297-.371-.682-.371a.74.74 0 0 0-.476.163c-.12.097-.104.22-.011.266l.246.141c.29-.093.61-.106.923-.2");
}

.ju-3ieb_x {
  d: path("M16.108 10.001h-.018q.064-.001.128.005q-.056-.006-.11-.005");
}

.k1-hbtbhm {
  stop-color: var(--svg-color--885e54, #885E54);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k3eoh3x-c {
  stop-color: var(--svg-color--a77b6c, #A77B6C);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kahu9wb3l {
  fill: var(--svg-color--a07364, #A07364);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kt1b6lbfw {
  stop-color: var(--svg-color--9a567d, #9A567D);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.m-5ct0byw {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.097 5.971l-.633.117a.306.306 0 1 1-.056-.606h1.04c.614 0 .818.619.843.83a1.4 1.4 0 0 0-1.194-.34");
}

.m554dhpjb {
  stop-color: var(--svg-color--bb9586, #BB9586);
}

.m8pucsqyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.668l.84.085a.21.21 0 0 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdab-tbej {
  fill: var(--svg-color--b78880, #B78880);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mv_j9hb5m {
  stop-color: var(--svg-color--634990, #634990);
  stop-opacity: 0;
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.nrezcp5le {
  d: path("M16.017 10.709c-.438.015-1.42.084-1.985.163c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a25 25 0 0 0-1.985-.163z");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oxvn1x5xs {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M16.535 7.575c.118-.208.297-.371.683-.371c.169 0 .331.046.476.163c.12.097.104.22.011.266l-.247.141c-.29-.093-.61-.106-.923-.2");
}

.p_tr_bcwq {
  stop-color: var(--svg-color--c09386, #C09386);
}

.p47p3ixdi {
  stop-color: var(--svg-color--a87c70, #A87C70);
  stop-opacity: 0;
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pom__eb7s {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.967 7.23a.62.62 0 0 0-.602.47c-.02.077.04.151.119.151h.99a.102.102 0 0 0 .101-.12a.62.62 0 0 0-.608-.501");
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.prw3-ibql {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m14.52 7.038l-.002.001a.12.12 0 0 1-.123-.204h.001l.002-.001l.004-.003l.014-.008l.052-.026a2 2 0 0 1 .182-.072c.15-.048.362-.088.59-.048a.12.12 0 1 1-.042.234c-.177-.03-.347 0-.476.041a1 1 0 0 0-.192.08z");
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.qg92x2blu {
  stop-color: var(--svg-color--af8375, #AF8375);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qmv39g7bi {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.76 4.368c-.502-.11-.954.391-1.006.577c.467 1.574 1.648 1.488 2.815 1.358c.698-.077.774.24.833.395c0-1.746-1.485-2.074-2.629-2.327z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r7kas8b0r {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rglphuhmg {
  stop-color: var(--svg-color--ad8273, #AD8273);
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s89mq5-5f {
  stop-color: var(--svg-color--9673d5, #9673D5);
  stop-opacity: 0;
}

.sduk0cbig {
  stop-color: var(--svg-color--9c6e69, #9C6E69);
}

.sen0n_b0o {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m17.685 6.835l-.061.102za.12.12 0 0 1-.122.204l-.002-.001l-.01-.005l-.04-.02a1 1 0 0 0-.153-.06a1 1 0 0 0-.476-.042a.12.12 0 1 1-.04-.234c.227-.04.438 0 .589.048a1.5 1.5 0 0 1 .248.106l.004.003z");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.ssyj8hboz {
  d: path("M13.948 8.542a.714.714 0 1 0 0-1.43a.714.714 0 0 0 0 1.43");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t48-l2bco {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M18.172 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.t8_yaabsm {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.028 9.12c-.231 0-.448-.056-.63-.153c-.063-.033-.13.04-.091.097a.858.858 0 0 0 1.443 0c.039-.06-.028-.13-.09-.097a1.34 1.34 0 0 1-.632.153");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tjku6kbhg {
  cx: 14.939px;
  cy: 7.52px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.088px;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.trk0d3lvr {
  d: path("M15.42 7.7c0-.128-.103-.213-.132-.24l-.128.125l.08.16z");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ue6n0w96y {
  d: path("M15.059 7.35a.396.396 0 0 0-.382.501h.765a.4.4 0 0 0-.384-.5");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.ukj380brt {
  stop-color: var(--svg-color--a585e1, #A585E1);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vd43a7ybz {
  stop-color: var(--svg-color--865653, #865653);
}

.vfl1x5hzz {
  fill: var(--svg-color--a47e69, #A47E69);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.vghwp6-5c {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M13.957 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vnfh0zkir {
  fill: var(--svg-color--a77b6c, #A77B6C);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
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

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vwxh7jegl {
  d: path("M18.171 8.542a.714.714 0 1 0 0-1.43a.714.714 0 0 0 0 1.43");
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w7ma6l7fs {
  d: path("m15.859 7.667l-.236.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.287-.167-.34 0");
}

.w83i6gbkm {
  d: path("M15.76 4.368c-.502-.11-.954.391-1.006.577c.467 1.574 1.648 1.488 2.815 1.358c.698-.077.774.24.833.395c0-1.746-1.485-2.074-2.629-2.327z");
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wzzru_b9g {
  d: path("M16.998 7.35a.396.396 0 0 1 .382.501h-.766a.398.398 0 0 1 .384-.5");
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xx5_pxj-t {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.09 7.23c.29 0 .535.2.602.47a.122.122 0 0 1-.12.151h-.99a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .608-.501");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yckxtx0he {
  d: path("M18.172 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
  stop-opacity: 0;
}

.ygruuqhoq {
  stop-color: var(--svg-color--885e54, #885E54);
  stop-opacity: 0;
}

.yiaq2oila {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.854 7.728l-.303.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.219-.167-.272 0");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yozsjebeb {
  fill: var(--svg-color--000, #000);
  d: path("M15.286 7.747a.226.226 0 0 0-.227-.227a.226.226 0 0 0-.202.331h.402a.2.2 0 0 0 .027-.104");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yxx_q1b1a {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.028 9.12c-.231 0-.448-.056-.63-.153c-.063-.033-.13.04-.091.097a.858.858 0 0 0 1.443 0c.039-.06-.028-.13-.09-.097a1.34 1.34 0 0 1-.632.153Z");
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

.z7rmu-ysc {
  stop-color: var(--svg-color--8a405c, #8A405C);
  stop-opacity: 0;
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.ze31rdbyh {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.zedm4_93e {
  stop-color: var(--svg-color--906663, #906663);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zepkmwb6a {
  fill: var(--svg-color--8569c7, #8569C7);
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.zjxboub4f {
  cx: 14.939px;
  cy: 7.52px;
  rx: 0.173px;
  ry: 0.088px;
}

.zlwhb3jwn {
  stop-color: var(--svg-color--9c6576, #9C6576);
  stop-opacity: 0;
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

</style>
