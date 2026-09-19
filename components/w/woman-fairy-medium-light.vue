<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOACDhc)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iEyq4SY)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#i2SsoJb)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iWslTEb)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#ijq6VRI)"><path class="er079sbvz"/></g><g filter="url(#ibPP0Xd)"><path class="ytl8wkbiv"/></g><g filter="url(#ihuk2re)"><path class="m8pucsqyt"/></g><g filter="url(#iTs4kae)"><path class="pv3dgeoha"/></g><g filter="url(#iLMTJeb)"><path fill="url(#iwV7UVb)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iUnBmNc)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iD0Zn1b)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#ix4gzTd)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#ik1K1CM)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iLsDbYd)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#im8ud3d)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iLwxiRc)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iVCeeLd)" clip-rule="evenodd" class="pl5fowbww"/><path fill="url(#iKR8ZAb)" clip-rule="evenodd" class="pl5fowbww"/></g><g filter="url(#iDFvyre)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#iYSW57D)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="c_ir2fb_m"/><path fill="url(#i7QnpSd)" class="eahf9fbrk"/><path fill="url(#iJU4nte)" class="eahf9fbrk"/><path fill="url(#i2RW5Nd)" class="j-tweow-u"/><path fill="url(#iCaNGJb)" class="j-tweow-u"/><path fill="url(#ib1SRrd)" class="j-tweow-u"/><path fill="url(#iHaKk0h)" class="j-tweow-u"/><path fill="url(#iuP6NMd)" class="bm7w23b9t"/><path fill="url(#iDv7Hjb)" class="bm7w23b9t"/><g filter="url(#iUsbsYc)"><path class="y29qm1cbe"/><path fill="url(#iqiBu3b)" class="r7kas8b0r"/><path fill="url(#i7dsj4d)" class="r7kas8b0r"/></g><path fill="url(#iVrmjge)" class="r7kas8b0r"/><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iRTRGab)" class="z30kudb-o"/><g filter="url(#iK7rpyb)"><path class="ryg6lupnq"/><path fill="url(#ivYsIjQ)" class="uu9c01xwt"/><path fill="url(#i8nGM4b)" class="uu9c01xwt"/></g><g filter="url(#i4C9fhX)"><path class="ze31rdbyh"/></g><g filter="url(#iGc5L6s)"><path class="sbo09h-_f"/><path fill="url(#iF2AuEd)" class="h2pt4jb3o"/><path fill="url(#ibLg2rc)" class="h2pt4jb3o"/></g><g filter="url(#iEy4gWc)"><path class="vbxfgjb_h"/></g><path fill="url(#iWroyTd)" class="nrezcp5le"/><path fill="url(#izNTKdc)" class="nrezcp5le"/><path fill="url(#iiD6wCc)" class="nrezcp5le"/><path fill="url(#iKByDMe)" class="nrezcp5le"/><path fill="url(#iBJnkMe)" class="nrezcp5le"/><path fill="url(#igkcOoS)" class="b6pcaeboe"/><path fill="url(#iUMlSIe)" class="b6pcaeboe"/><g filter="url(#ikckSWs)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#iLG222i)"><path stroke="url(#iW0sNjd)" class="iqsdfibon"/></g><path fill="url(#irGgnec)" class="f28zyusup"/><path fill="url(#iHeluSb)" class="ju-3ieb_x"/><g filter="url(#ibU7LiZ)"><path fill="url(#ihBmkZd)" class="ssyj8hboz"/></g><g filter="url(#iPeYhPb)"><path fill="url(#irxKige)" class="vwxh7jegl"/><path fill="url(#iYwZdLb)" class="vwxh7jegl"/></g><g filter="url(#iweO5ne)"><path class="bvbh8ogwl"/><path fill="url(#icGuNfb)" class="yckxtx0he"/></g><g filter="url(#iWbtWEd)"><path class="etard7r3j"/><path fill="url(#iOeQvzb)" class="ei67qgb4y"/></g><g filter="url(#iBvLiad)"><path fill="url(#iiquh6d)" class="lxby7wb_n"/><path fill="url(#i70TPYc)" class="lxby7wb_n"/><path fill="url(#iMpquWd)" class="lxby7wb_n"/><path fill="url(#iMZb7Ae)" class="lxby7wb_n"/><path fill="url(#ipZVvwc)" class="lxby7wb_n"/><path fill="url(#ipigX0c)" class="lxby7wb_n"/><path fill="url(#iYUJIse)" class="lxby7wb_n"/></g><path fill="url(#ilSo9fd)" class="gq9codbwo"/><path fill="url(#iiZdUpF)" class="gq9codbwo"/><g filter="url(#iRLrVIc)"><path class="uw5x4tdmr"/></g><g filter="url(#iIIPvLe)"><path class="jjnjgjblt"/><path fill="url(#iLcL8MU)" class="w7ma6l7fs"/><path fill="url(#i9RcSQc)" class="w7ma6l7fs"/><path fill="url(#icmqSab)" class="w7ma6l7fs"/></g><g filter="url(#iTlVyKc)"><path stroke="url(#iurIvSg)" class="yxx_q1b1a"/></g><path class="u87dk3b1h"/><g filter="url(#it9z4Xn)"><path class="l_s-5t8ve"/></g><g filter="url(#iFdVeXc)"><path class="f68nxcbkg"/></g><g filter="url(#iW4G4dK)"><path class="n58hp1d6u"/></g><g filter="url(#i7Zb8wb)"><path clip-rule="evenodd" class="wzjebnx6c"/></g><path class="xx5_pxj-t"/><path fill="url(#iuHHFWG)" class="wzzru_b9g"/><path class="bq010tbbk"/><g filter="url(#iz71w7b)"><path class="dtrv1ybfs"/><path fill="url(#i8wNiCe)" class="h25f5pelt"/></g><g filter="url(#icaRg5R)"><path fill="url(#ipgkKTb)" class="dg7g-pbpg"/></g><path class="pom__eb7s"/><path fill="url(#ivioMBY)" class="ue6n0w96y"/><path class="yozsjebeb"/><g filter="url(#iNcwpKb)"><path fill="url(#igEo7Ee)" class="trk0d3lvr"/></g><g filter="url(#iFDmBPb)"><ellipse transform="rotate(-27.914 14.94 7.52)" class="tjku6kbhg"/><ellipse fill="url(#ixCbqmu)" transform="rotate(-27.914 14.94 7.52)" class="zjxboub4f"/></g><g filter="url(#i1uSnMb)"><path fill="url(#iVz7L4Z)" class="xh3ravbko"/><path fill="url(#ihGswOc)" class="xh3ravbko"/><path fill="url(#i99hLRU)" class="xh3ravbko"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="iUnBmNc" cx="0" cy="0" r="1" gradientTransform="matrix(.77392 -1.60737 3.6649 1.76458 18.112 10.411)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iD0Zn1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.8384 2.42473 -2.2697 -.7848 15.73 8.61)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="ix4gzTd" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 5.77 7.038)scale(1.77133 2.18041)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="ik1K1CM" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 4.878 7.572)scale(.79072 .71872)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iLsDbYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03437 -.23068 .3391 -1.52054 14.116 7.263)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="im8ud3d" cx="0" cy="0" r="1" gradientTransform="matrix(.95999 1.40644 -2.45444 1.67531 14.324 4.465)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iLwxiRc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 8.074 6.7)scale(.72684 1.01573)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iVCeeLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81853 .23813 -.51814 -1.78101 19.362 7.45)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iKR8ZAb" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 8.736 6.304)scale(1.5204 2.42247)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="ib1SRrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.7132 -.85217 -.06096 15.406 25.564)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="k6zy9n07l"/><stop offset="1" class="m22s2i1fh"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="i7dsj4d" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="s-dztxv8u"/><stop offset="1" class="wm2hnkwbm"/></radialGradient><radialGradient id="iVrmjge" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .42629 -1.32724 2.2135 16.606 22.867)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="dvlr87bav"/><stop offset="1" class="h2aikfbxt"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iRTRGab" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="md09g_bwr"/><stop offset="1" class="vudwjbw9p"/></radialGradient><radialGradient id="ivYsIjQ" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="n6c_0ja6r"/><stop offset="1" class="sxlwo8bvv"/></radialGradient><radialGradient id="i8nGM4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="p77zblbaj"/><stop offset="1" class="gvz69mboo"/></radialGradient><radialGradient id="iF2AuEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="z1f5d8bxu"/><stop offset="1" class="s8gxoccyp"/></radialGradient><radialGradient id="ibLg2rc" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="t_55psbku"/><stop offset="1" class="bwfo2x8_b"/></radialGradient><radialGradient id="iiD6wCc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="g7dj32byf"/><stop offset="1" class="mv_j9hb5m"/></radialGradient><radialGradient id="igkcOoS" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 1.25508 -2.35578 1.02647 15.148 10.137)" gradientUnits="userSpaceOnUse"><stop class="q_i4prb1m"/><stop offset="1" class="osml3-ahx"/></radialGradient><radialGradient id="iUMlSIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.95899 .62292 -.3324 -.51174 16.987 10.352)" gradientUnits="userSpaceOnUse"><stop class="sb6wk2byh"/><stop offset="1" class="oh250pbjd"/></radialGradient><radialGradient id="irxKige" cx="0" cy="0" r="1" gradientTransform="matrix(1.10507 -.5023 .61329 1.34924 17.822 8.022)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iYwZdLb" cx="0" cy="0" r="1" gradientTransform="matrix(.44277 .12651 -.06651 .23278 18.276 7.036)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="icGuNfb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 31.192 -46.5)scale(.5792)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iOeQvzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.54025 0 0 -.51678 13.957 7.827)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iiquh6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8874 1.33147 -1.78215 -3.86473 17.298 7.589)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="i70TPYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.93666 .49544 -.42034 -.79469 16.872 7.898)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iMpquWd" cx="0" cy="0" r="1" gradientTransform="matrix(.37157 -1.79591 2.27869 .47145 15.06 10.6)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iMZb7Ae" cx="0" cy="0" r="1" gradientTransform="scale(4.4761 3.30203)rotate(90 .66 2.92)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="z1_e0qpta"/></radialGradient><radialGradient id="ipZVvwc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.545 .34229 -.58932 -4.3817 16.311 8.625)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ipigX0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5109 .73449 0 17.05 7.403)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iYUJIse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6038 .692 0 15.177 7.442)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="ilSo9fd" cx="0" cy="0" r="1" gradientTransform="matrix(-.598 0 0 -1.96866 18.29 8.063)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iiZdUpF" cx="0" cy="0" r="1" gradientTransform="matrix(.51334 1.873 -3.87045 1.06079 14.918 5.144)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iLcL8MU" cx="0" cy="0" r="1" gradientTransform="matrix(-.30965 -1.0876 .62235 -.17719 16.377 8.386)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iuHHFWG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3602 -.57294 0 16.997 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8wNiCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10296 -.13269 .18267 -.14175 16.896 7.6)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivioMBY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3602 -.57294 0 15.06 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixCbqmu" cx="0" cy="0" r="1" gradientTransform="matrix(-.00343 -.21935 .26366 -.00413 14.932 7.66)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVz7L4Z" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.084 7.46)scale(2.16342 3.0763)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="ihGswOc" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 6.673 8.963)scale(1.47384 2.63085)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i99hLRU" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 10.435 -1.255)scale(3.20123 2.86556)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iOACDhc" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1154" result="effect2_innerShadow_4002_1154"/></filter><filter id="iEyq4SY" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1154" result="effect2_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1154" result="effect3_innerShadow_4002_1154"/></filter><filter id="i2SsoJb" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1154" result="effect2_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1154" result="effect3_innerShadow_4002_1154"/></filter><filter id="iWslTEb" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="ijq6VRI" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1154" result="effect2_dropShadow_4002_1154"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1154" result="shape"/></filter><filter id="ibPP0Xd" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1154" result="effect2_dropShadow_4002_1154"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1154" result="shape"/></filter><filter id="ihuk2re" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1154" result="effect2_dropShadow_4002_1154"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1154" result="shape"/></filter><filter id="iTs4kae" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1154" result="effect2_dropShadow_4002_1154"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1154" result="shape"/></filter><filter id="iLMTJeb" width="6.918" height="7.418" x="12.695" y="3.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iDFvyre" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iYSW57D" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iUsbsYc" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iK7rpyb" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.505882 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.454902 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1154" result="effect2_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.6 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1154" result="effect3_innerShadow_4002_1154"/></filter><filter id="i4C9fhX" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iGc5L6s" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.537255 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iEy4gWc" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.466667 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="ikckSWs" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1154" result="effect2_innerShadow_4002_1154"/></filter><filter id="iLG222i" width="4.609" height="5.161" x="18.951" y="9.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".25"/></filter><filter id="ibU7LiZ" width="1.579" height="1.679" x="13.234" y="7.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iPeYhPb" width="1.429" height="1.679" x="17.457" y="6.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iweO5ne" width="1.354" height="1.354" x="17.495" y="7.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".1"/></filter><filter id="iWbtWEd" width="1.354" height="1.354" x="13.28" y="7.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".1"/></filter><filter id="iBvLiad" width="4.524" height="4.929" x="13.766" y="5.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iRLrVIc" width="1.833" height="2.191" x="15.04" y="7.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".25"/></filter><filter id="iIIPvLe" width="1.033" height="1.391" x="15.512" y="7.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".05"/></filter><filter id="iTlVyKc" width="1.766" height=".8" x="15.145" y="8.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".05"/></filter><filter id="it9z4Xn" width="1.444" height=".571" x="16.335" y="7.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iFdVeXc" width="1.444" height=".571" x="14.278" y="7.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iW4G4dK" width="1.2" height=".596" x="14.338" y="6.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="i7Zb8wb" width="1.2" height=".596" x="16.743" y="6.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1154"/></filter><filter id="iz71w7b" width=".461" height=".42" x="16.616" y="7.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".05"/></filter><filter id="icaRg5R" width=".618" height=".628" x="16.933" y="7.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".1"/></filter><filter id="iNcwpKb" width=".66" height=".684" x="14.96" y="7.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".1"/></filter><filter id="iFDmBPb" width=".517" height=".424" x="14.681" y="7.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".05"/></filter><filter id="i1uSnMb" width="3.936" height="2.544" x="14.566" y="4.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1154" stdDeviation=".05"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iwV7UVb" x1="18.112" x2="15.091" y1="4.741" y2="10.337" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="i2RW5Nd" x1="15.345" x2="13.875" y1="24.348" y2="24.348" gradientUnits="userSpaceOnUse"><stop offset=".267" class="gvrh5ob2r"/><stop offset=".945" class="zx2ao6bwg"/></linearGradient><linearGradient id="iCaNGJb" x1="15.517" x2="15.017" y1="26.036" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="ff90ucc6c"/><stop offset="1" class="a5twm1ncx"/></linearGradient><linearGradient id="iHaKk0h" x1="13.318" x2="13.75" y1="24.833" y2="24.833" gradientUnits="userSpaceOnUse"><stop class="p5rcrxbls"/><stop offset="1" class="w4_s79ciy"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="iqiBu3b" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="rr5fu4pew"/><stop offset="1" class="u39dyibqi"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="iW0sNjd" x1="22.451" x2="19.857" y1="11.683" y2="13.527" gradientUnits="userSpaceOnUse"><stop offset=".453" class="bi_gnlatu"/><stop offset="1" class="qqsiimfct"/></linearGradient><linearGradient id="irGgnec" x1="12.937" x2="19.259" y1="10.014" y2="10.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeluSb" x1="12.937" x2="19.259" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ihBmkZd" x1="13.234" x2="14.547" y1="7.866" y2="7.866" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="i9RcSQc" x1="15.564" x2="15.943" y1="8.394" y2="8.44" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="icmqSab" x1="16.028" x2="16.028" y1="8.773" y2="8.502" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iurIvSg" x1="15.704" x2="15.905" y1="9.429" y2="9.042" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="ipgkKTb" x1="17.343" x2="17.203" y1="7.586" y2="7.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igEo7Ee" x1="15.39" x2="15.251" y1="7.586" y2="7.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy-medium-light" /></template>
<style>
.a5twm1ncx {
  stop-color: var(--svg-color--dea386, #DEA386);
  stop-opacity: 0;
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bi_gnlatu {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bm7w23b9t {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.bq010tbbk {
  fill: var(--svg-color--000, #000);
  d: path("M16.771 7.747c0-.126.1-.227.227-.227a.226.226 0 0 1 .202.331h-.402a.2.2 0 0 1-.027-.104");
}

.bvbh8ogwl {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M18.172 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.bwfo2x8_b {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
}

.c_ir2fb_m {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
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

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
}

.dg7g-pbpg {
  d: path("M17.35 7.695a.37.37 0 0 0-.102-.206l-.115.127l.052.101z");
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dtrv1ybfs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.969 7.434c.028.038-.03.084-.098.134c-.067.05-.117.086-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.dvlr87bav {
  stop-color: var(--svg-color--b88067, #B88067);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eahf9fbrk {
  d: path("M13.267 16.39v-.862h5.525v.82a49 49 0 0 1-5.525.042");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.ei67qgb4y {
  d: path("M13.957 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.er079sbvz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.etard7r3j {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M13.957 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
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

.f28zyusup {
  d: path("M16.253 10.001q.166.009.338.022c-.114-.008-.224-.017-.338-.022");
}

.f68nxcbkg {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.521 7.575c-.118-.208-.297-.371-.682-.371a.74.74 0 0 0-.476.163c-.12.097-.104.22-.011.266l.246.141c.29-.093.61-.106.923-.2");
}

.ff90ucc6c {
  stop-color: var(--svg-color--dea386, #DEA386);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g7dj32byf {
  stop-color: var(--svg-color--402d65, #402D65);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq9codbwo {
  d: path("M13.77 7.267h.005l-.004-.118l-.005-.136c.01-.421.255-.584.36-.639l.023-.009l.022-.009c.237-.109.428-.299.528-.548l.037-.086c.036-.086.15-.1.205-.023c.318.467.851.743 1.416.743h1.43c.08 0 .48.039.504.592l-.053 1.364c-.055 1.244-1.026 2.08-2.213 2.08c-1.186 0-2.157-.836-2.212-2.08z");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gvrh5ob2r {
  stop-color: var(--svg-color--f4bba1, #F4BBA1);
}

.gvz69mboo {
  stop-color: var(--svg-color--ac596b, #AC596B);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h25f5pelt {
  d: path("M16.969 7.434c.028.038-.03.084-.098.134c-.067.05-.117.086-.145.048s.003-.11.07-.16s.145-.06.173-.022");
}

.h2aikfbxt {
  stop-color: var(--svg-color--c6846b, #C6846B);
  stop-opacity: 0;
}

.h2pt4jb3o {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.iqsdfibon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.701 12.745l2.672 1.045a.1.1 0 0 0 .136-.084l.302-3.57");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jjnjgjblt {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.859 7.667l-.236.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.287-.167-.34 0");
}

.ju-3ieb_x {
  d: path("M16.108 10.001h-.018q.064-.001.128.005q-.056-.006-.11-.005");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k6zy9n07l {
  stop-color: var(--svg-color--a87973, #A87973);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
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

.l_s-5t8ve {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.535 7.575c.118-.208.297-.371.683-.371c.169 0 .331.046.476.163c.12.097.104.22.011.266l-.247.141c-.29-.093-.61-.106-.923-.2");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxby7wb_n {
  d: path("m13.77 7.149l-.004-.136c.01-.421.255-.584.36-.639l.023-.009l.022-.009c.237-.109.428-.299.528-.548l.037-.086c.036-.086.15-.1.205-.023c.318.467.851.743 1.416.743h1.43c.08 0 .48.039.504.592l-.053 1.364c-.055 1.244-1.026 2.08-2.213 2.08c-1.186 0-2.157-.836-2.212-2.08z");
}

.m22s2i1fh {
  stop-color: var(--svg-color--d7a18a, #D7A18A);
  stop-opacity: 0;
}

.m8pucsqyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.668l.84.085a.21.21 0 0 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md09g_bwr {
  stop-color: var(--svg-color--dc9f87, #DC9F87);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv_j9hb5m {
  stop-color: var(--svg-color--634990, #634990);
  stop-opacity: 0;
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n58hp1d6u {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m14.52 7.038l-.002.001a.12.12 0 0 1-.123-.204h.001l.002-.001l.004-.003l.014-.008l.052-.026a2 2 0 0 1 .182-.072c.15-.048.362-.088.59-.048a.12.12 0 1 1-.042.234c-.177-.03-.347 0-.476.041a1 1 0 0 0-.192.08z");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n6c_0ja6r {
  stop-color: var(--svg-color--bc826b, #BC826B);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nrezcp5le {
  d: path("M16.017 10.709c-.438.015-1.42.084-1.985.163c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a25 25 0 0 0-1.985-.163z");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh250pbjd {
  stop-color: var(--svg-color--df9e84, #DF9E84);
  stop-opacity: 0;
}

.osml3-ahx {
  stop-color: var(--svg-color--e1a891, #E1A891);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p5rcrxbls {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p77zblbaj {
  stop-color: var(--svg-color--ac596b, #AC596B);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl5fowbww {
  fill-rule: evenodd;
  d: path("M19.218 8.453a1.46 1.46 0 0 0 .025-1.213h.002a1.4 1.4 0 0 0-.125-.228v-.001a1.44 1.44 0 0 1-.234-.786V6.22c0-.809-.656-1.465-1.465-1.465a.24.24 0 0 1-.202-.103a1.468 1.468 0 0 0-2.381 0a.25.25 0 0 1-.202.103h-.038A1.465 1.465 0 0 0 13.17 6.22v.005c0 .278-.081.552-.234.786v.002a1.47 1.47 0 0 0-.099 1.44a.23.23 0 0 1 0 .202a1.427 1.427 0 0 0 1.285 2.053h3.81a1.427 1.427 0 0 0 1.285-2.053a.23.23 0 0 1 0-.202m-5.443-1.186h-.005l.532 1.046c.055 1.244.54 0 1.726 0s1.704 1.384 1.758.14l.505-1.42c-.024-.552-.425-.59-.505-.59h-1.43a1.72 1.72 0 0 1-1.415-.744a.117.117 0 0 0-.205.023l-.037.086c-.1.25-.29.44-.528.548l-.022.01l-.023.008c-.105.055-.35.218-.36.64l.005.135z");
}

.pom__eb7s {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.967 7.23a.62.62 0 0 0-.602.47c-.02.077.04.151.119.151h.99a.102.102 0 0 0 .101-.12a.62.62 0 0 0-.608-.501");
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q_i4prb1m {
  stop-color: var(--svg-color--d08a70, #D08A70);
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qqsiimfct {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r7kas8b0r {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rr5fu4pew {
  stop-color: var(--svg-color--dba697, #DBA697);
}

.ryg6lupnq {
  fill: var(--svg-color--e1ab90, #E1AB90);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s-dztxv8u {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
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

.s8gxoccyp {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
  stop-opacity: 0;
}

.sb6wk2byh {
  stop-color: var(--svg-color--df9e84, #DF9E84);
}

.sbo09h-_f {
  fill: var(--svg-color--daa788, #DAA788);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.ssyj8hboz {
  d: path("M13.948 8.542a.714.714 0 1 0 0-1.43a.714.714 0 0 0 0 1.43");
}

.sxlwo8bvv {
  stop-color: var(--svg-color--bc826b, #BC826B);
}

.t_55psbku {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tjku6kbhg {
  cx: 14.939px;
  cy: 7.52px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.088px;
}

.trk0d3lvr {
  d: path("M15.42 7.7c0-.128-.103-.213-.132-.24l-.128.125l.08.16z");
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u39dyibqi {
  stop-color: var(--svg-color--dba697, #DBA697);
  stop-opacity: 0;
}

.u87dk3b1h {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.028 9.12c-.231 0-.448-.056-.63-.153c-.063-.033-.13.04-.091.097a.858.858 0 0 0 1.443 0c.039-.06-.028-.13-.09-.097a1.34 1.34 0 0 1-.632.153");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ue6n0w96y {
  d: path("M15.059 7.35a.396.396 0 0 0-.382.501h.765a.4.4 0 0 0-.384-.5");
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

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uw5x4tdmr {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.854 7.728l-.303.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.219-.167-.272 0");
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbxfgjb_h {
  fill: var(--svg-color--dfa286, #DFA286);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vudwjbw9p {
  stop-color: var(--svg-color--b5737a, #B5737A);
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
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

.w4_s79ciy {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
  stop-opacity: 0;
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w7ma6l7fs {
  d: path("m15.859 7.667l-.236.755a.24.24 0 0 0 .23.31h.35a.24.24 0 0 0 .231-.31l-.236-.755c-.05-.167-.287-.167-.34 0");
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wm2hnkwbm {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
  stop-opacity: 0;
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.wzjebnx6c {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m17.685 6.835l-.061.102za.12.12 0 0 1-.122.204l-.002-.001l-.01-.005l-.04-.02a1 1 0 0 0-.153-.06a1 1 0 0 0-.476-.042a.12.12 0 1 1-.04-.234c.227-.04.438 0 .589.048a1.5 1.5 0 0 1 .248.106l.004.003z");
}

.wzzru_b9g {
  d: path("M16.998 7.35a.396.396 0 0 1 .382.501h-.766a.398.398 0 0 1 .384-.5");
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xh3ravbko {
  d: path("M15.76 4.368c-.502-.11-1.041.425-1.094.61c.685 1.608 1.736 1.455 2.903 1.325c.698-.077.774.24.833.395c-.193-1.801-1.496-2.077-2.642-2.33");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xx5_pxj-t {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.09 7.23c.29 0 .535.2.602.47a.122.122 0 0 1-.12.151h-.99a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .608-.501");
}

.y29qm1cbe {
  fill: var(--svg-color--e7ae99, #E7AE99);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.063.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yckxtx0he {
  d: path("M18.172 8.304a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
  stop-opacity: 0;
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yozsjebeb {
  fill: var(--svg-color--000, #000);
  d: path("M15.286 7.747a.226.226 0 0 0-.227-.227a.226.226 0 0 0-.202.331h.402a.2.2 0 0 0 .027-.104");
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

.z1_e0qpta {
  stop-color: var(--svg-color--bc7a76, #BC7A76);
}

.z1f5d8bxu {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.ze31rdbyh {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
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

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zx2ao6bwg {
  stop-color: var(--svg-color--d79c86, #D79C86);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
