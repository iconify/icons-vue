<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUIqbRb)"><path fill="url(#iK6LrBc)" class="tylzkc2ni"/><path fill="url(#iL6S3NL)" class="tylzkc2ni"/><path fill="url(#i7SB6hF)" class="tylzkc2ni"/><path fill="url(#iIisrre)" class="tylzkc2ni"/><path fill="url(#iKb0oSc)" class="tylzkc2ni"/><path fill="url(#iS8A5ld)" class="tylzkc2ni"/><path fill="url(#iWpHqLL)" class="tylzkc2ni"/></g><g filter="url(#in5Mtyd)"><path class="gn_qypbgw"/></g><path fill="url(#iIJ4Y6c)" class="itk8q2bqv"/><g filter="url(#izcwbKb)"><path fill="url(#iz0HgDe)" class="zvht3bbsb"/></g><path fill="url(#i84300c)" class="p-43r8bct"/><path fill="url(#iGVMdeX)" class="p-43r8bct"/><g filter="url(#iyecqow)"><path fill="url(#i046Wmd)" class="jl_5q555j"/><path fill="url(#i5dUYmd)" class="jl_5q555j"/></g><g filter="url(#ivFguie)"><path fill="url(#i7NrZfb)" class="gg7v2sgvk"/><path fill="url(#iXwwCbc)" class="gg7v2sgvk"/><path fill="url(#iF5hAue)" class="gg7v2sgvk"/><path fill="url(#iyDhdgc)" class="gg7v2sgvk"/><path fill="url(#iITP3Yc)" class="gg7v2sgvk"/><path fill="url(#irlsIur)" class="gg7v2sgvk"/><path fill="url(#icD4kBd)" class="gg7v2sgvk"/><path fill="url(#iYi4KQd)" class="gg7v2sgvk"/></g><path fill="url(#ih1tmpT)" class="gg7v2sgvk"/><path fill="url(#iA61mHd)" class="gg7v2sgvk"/><path fill="url(#iGFe5Qb)" class="gg7v2sgvk"/><path fill="url(#iunmYUK)" class="gg7v2sgvk"/><g filter="url(#iROQBrz)"><path stroke="url(#iOPfD1b)" class="sc9s-1bed"/></g><g filter="url(#ihAV9Gd)"><path stroke="url(#iBoQFCd)" class="qpsqlesux"/></g><g filter="url(#iY2BPwd)"><path stroke="url(#i7Use1c)" class="s727t-8_q"/></g><g filter="url(#id402Ib)"><path class="vrorbj-kg"/></g><g filter="url(#iDVlU7d)"><path class="uies7db_y"/><path fill="url(#iq8q8id)" class="e7jbu0blg"/><path fill="url(#iFR3rdb)" class="e7jbu0blg"/><path fill="url(#iqLkaAd)" class="e7jbu0blg"/></g><g filter="url(#iryLlCc)"><path fill="url(#iSzPwib)" class="pgp143bck"/></g><path fill="url(#iFmsQye)" class="xu7iftcsg"/><g filter="url(#iIe32Jd)"><path fill="url(#iDQN16d)" class="kx-u1f1nr"/></g><g filter="url(#iSjFUbd)"><path fill="url(#iGiUtke)" class="b9vbofbwl"/></g><g filter="url(#iNaG9Td)"><path fill="url(#imCvufb)" class="pvvyv9bsi"/></g><path fill="url(#iHhx7qd)" class="pvvyv9bsi"/><path fill="url(#i6GtDof)" class="pvvyv9bsi"/><path fill="url(#inLvWoC)" class="pvvyv9bsi"/><path fill="url(#is3aqpd)" class="pvvyv9bsi"/><path fill="url(#iE0NYnb)" class="pvvyv9bsi"/><path fill="url(#iE8Q53b)" class="pvvyv9bsi"/><path fill="url(#ih56C1b)" class="pvvyv9bsi"/><g filter="url(#iAjqokc)"><path class="xbk-y3bqk"/></g><path class="nxfagccjp"/><path fill="url(#ikemhme)" class="n6mjte-pr"/><path fill="url(#id71Exe)" class="n6mjte-pr"/><path fill="url(#i0anx7d)" class="n6mjte-pr"/><path fill="url(#i6Un3wd)" class="n6mjte-pr"/><path fill="url(#i9jLwvb)" class="n6mjte-pr"/><g filter="url(#irUyIAd)"><path stroke="url(#iarC7eu)" class="iibz_cc8h"/></g><path class="e62kxsb4l"/><g filter="url(#iR7Hxei)"><path class="j-y2d-bpp"/></g><g filter="url(#iFZvVsd)"><path class="ewg_wtbvw"/></g><g filter="url(#i5Icotd)"><path class="dx7rnx6ra"/></g><g filter="url(#itd3Iib)"><path clip-rule="evenodd" class="t8zak5bmc"/></g><path class="tlvzcsbls"/><path fill="url(#iBhIerD)" class="sidjyzc1j"/><path class="dfd63o21n"/><g filter="url(#i3E2sjd)"><path class="krhwxbssl"/><path fill="url(#ijnnatW)" class="ktg8q2baj"/></g><g filter="url(#i4hekNe)"><path fill="url(#ijtHQge)" class="csx3pkbqc"/></g><path class="i736akkjc"/><path fill="url(#igrTQMc)" class="lhvnpmb3c"/><path class="ngxjebrpy"/><g filter="url(#i4PCvUb)"><path fill="url(#i8APABb)" class="efontmzot"/></g><g filter="url(#iBj1LqO)"><ellipse transform="rotate(-27.914 15.96 6.798)" class="w1evdl1rb"/><ellipse fill="url(#iBXmUIt)" transform="rotate(-27.914 15.96 6.798)" class="bizlpnzzl"/></g><g filter="url(#iZTZXee)"><path class="lyd9g1b-v"/></g><g filter="url(#im4pBed)"><path class="pk4gvbx0m"/></g><g filter="url(#i1Ov0jd)"><path fill="url(#idPHgob)" class="z1wxhzofg"/></g><g filter="url(#i8VuHPH)"><path fill="url(#iYSVVzp)" class="m7l8ktb_c"/></g><g filter="url(#iCDnd6d)"><path fill="url(#iNOPARb)" class="e33ktg_du"/><path fill="url(#i2R6tHe)" class="e33ktg_du"/><path fill="url(#iqQEroj)" class="e33ktg_du"/></g><g filter="url(#ihtZ4Zc)"><path class="ye462pblv"/><path fill="url(#iRkDUub)" class="opga4-hbt"/><path fill="url(#icbotye)" class="opga4-hbt"/><path fill="url(#iaPXNua)" class="opga4-hbt"/></g><g filter="url(#idd4qPd)"><path fill="url(#iXvc2gd)" class="mz6q3lszi"/></g><g filter="url(#i1GfQze)"><path fill="url(#i2B994k)" class="q13sv5b2f"/></g><g filter="url(#iRLQzid)"><path stroke="url(#iDalP4O)" class="r1waaobic"/></g><defs><radialGradient id="iK6LrBc" cx="0" cy="0" r="1" gradientTransform="matrix(.15624 10.48184 -9.82618 .14647 19.292 2.465)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="pquvpov8y"/><stop offset="1" class="ols1i2kaq"/></radialGradient><radialGradient id="iL6S3NL" cx="0" cy="0" r="1" gradientTransform="rotate(-89.469 11.518 -6.177)scale(1.68465 4.20396)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="st4hs763z"/><stop offset="1" class="rl7em7bjk"/></radialGradient><radialGradient id="i7SB6hF" cx="0" cy="0" r="1" gradientTransform="matrix(.92188 1.41941 -1.91842 1.24597 15.776 2.293)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="zn1rvob2u"/><stop offset="1" class="fzv28epeh"/></radialGradient><radialGradient id="iIisrre" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 -1.5286 1.87096 3.21293 19.635 9.796)" gradientUnits="userSpaceOnUse"><stop class="kawgt3bsr"/><stop offset="1" class="tgd5bcc3y"/></radialGradient><radialGradient id="iKb0oSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06249 3.24436 -2.44347 -.8002 14.167 14.912)" gradientUnits="userSpaceOnUse"><stop class="ynngk8bxm"/><stop offset="1" class="s1hry0blp"/></radialGradient><radialGradient id="iS8A5ld" cx="0" cy="0" r="1" gradientTransform="rotate(140.722 5.018 8.561)scale(6.7015 2.77997)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="grlhkzb5c"/><stop offset="1" class="m62n6lejs"/></radialGradient><radialGradient id="iWpHqLL" cx="0" cy="0" r="1" gradientTransform="rotate(140.56 5.939 7.497)scale(4.32433 3.77651)" gradientUnits="userSpaceOnUse"><stop class="jpih75bxh"/><stop offset="1" class="bkzx2xbnc"/></radialGradient><radialGradient id="iIJ4Y6c" cx="0" cy="0" r="1" gradientTransform="matrix(12.502 -3.897 4.76721 15.29373 10.857 25.03)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iz0HgDe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.559)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="i84300c" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.887)" gradientUnits="userSpaceOnUse"><stop class="sn41dmbim"/><stop offset="1" class="yvpamkx_l"/></radialGradient><radialGradient id="i046Wmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95313 .90937 -.4986 -.5226 25.737 7.27)" gradientUnits="userSpaceOnUse"><stop class="tl-riq-5r"/><stop offset=".611" class="zfvcixbyw"/></radialGradient><radialGradient id="i5dUYmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.04224 -.75 .57465 -.03236 25.182 8.7)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="aa79y-bxe"/><stop offset="1" class="knj7mgbph"/></radialGradient><radialGradient id="i7NrZfb" cx="0" cy="0" r="1" gradientTransform="rotate(159 8.582 8.051)scale(4.71973 6.48913)" gradientUnits="userSpaceOnUse"><stop class="a4m3534rg"/><stop offset="1" class="jekb5o0nb"/></radialGradient><radialGradient id="iF5hAue" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 4.11135 14.48 17.184)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="y0a-8tbvz"/><stop offset="1" class="ryny_ubjw"/></radialGradient><radialGradient id="iyDhdgc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.509 15.765 2.028)scale(5.76427 2.15458)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="gpjj60boc"/><stop offset="1" class="js8y_db3g"/></radialGradient><radialGradient id="iITP3Yc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14062 3.15625 -1.12664 .40715 23.761 10.824)" gradientUnits="userSpaceOnUse"><stop class="r7vltcbae"/><stop offset="1" class="gu1n7hb8i"/></radialGradient><radialGradient id="irlsIur" cx="0" cy="0" r="1" gradientTransform="rotate(-132.761 11.006 3.375)scale(1.90622 1.91545)" gradientUnits="userSpaceOnUse"><stop class="hilc70b9p"/><stop offset="1" class="v8-b80bcd"/></radialGradient><radialGradient id="icD4kBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 -1.89063 3.41696 -.90363 24.964 15.48)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="d08nthbva"/><stop offset="1" class="n02h-lbzo"/></radialGradient><radialGradient id="iYi4KQd" cx="0" cy="0" r="1" gradientTransform="rotate(155.579 7.478 6.662)scale(3.17465 2.03239)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="glz-c5bvr"/><stop offset="1" class="obylexqck"/></radialGradient><radialGradient id="ih1tmpT" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 4.60938 14.12 16.887)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="azzh1940u"/><stop offset="1" class="l336a0pec"/></radialGradient><radialGradient id="iGFe5Qb" cx="0" cy="0" r="1" gradientTransform="rotate(133.468 3.633 10.369)scale(2.48567 1.45387)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ztn7pxbjf"/><stop offset="1" class="wcbv0nbwv"/></radialGradient><radialGradient id="iunmYUK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 1.58593 -.17358 -.19496 13.003 15.37)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="n4lm9l72r"/><stop offset="1" class="zshz1kb8t"/></radialGradient><radialGradient id="iq8q8id" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17187 -1.23438 .5687 -.5399 16.854 14.37)" gradientUnits="userSpaceOnUse"><stop class="rd_1vj1uu"/><stop offset="1" class="w4wjacb9v"/></radialGradient><radialGradient id="iFR3rdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.26562 -.57617 0 17.413 13.293)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ookdrzgqt"/><stop offset="1" class="zku_rzyyo"/></radialGradient><radialGradient id="iqLkaAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4707 1.41406 -.31529 -.32792 21.136 13.137)" gradientUnits="userSpaceOnUse"><stop class="gwqfskb8v"/><stop offset="1" class="n7-hw2b3h"/></radialGradient><radialGradient id="iFmsQye" cx="0" cy="0" r="1" gradientTransform="matrix(-.66406 .65625 -.45034 -.4557 20.971 6.793)" gradientUnits="userSpaceOnUse"><stop class="ga8awzqfa"/><stop offset="1" class="j391rbtek"/></radialGradient><radialGradient id="iDQN16d" cx="0" cy="0" r="1" gradientTransform="rotate(90 6.528 13.736)scale(.63475)" gradientUnits="userSpaceOnUse"><stop class="ok0xogb6i"/><stop offset="1" class="a680lr2dp"/></radialGradient><radialGradient id="iGiUtke" cx="0" cy="0" r="1" gradientTransform="rotate(106.949 4.606 8.868)scale(.85756)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="vopejgz3x"/><stop offset="1" class="shpp5nbho"/></radialGradient><radialGradient id="imCvufb" cx="0" cy="0" r="1" gradientTransform="rotate(144.245 8.494 6.415)scale(4.42841 3.31615)" gradientUnits="userSpaceOnUse"><stop class="fs81_6bpu"/><stop offset=".755" class="yiq9sac5t"/></radialGradient><radialGradient id="iHhx7qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.48957 -5.92174 0 17.41 6.246)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="rau17bcwj"/><stop offset="1" class="dbc20iija"/></radialGradient><radialGradient id="i6GtDof" cx="0" cy="0" r="1" gradientTransform="matrix(-.90623 2 -1.87388 -.84908 17.12 4.424)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="mmf02ltsv"/><stop offset="1" class="otc9m4bci"/></radialGradient><radialGradient id="inLvWoC" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 9.25 5.577)scale(1.42145 2.26202)" gradientUnits="userSpaceOnUse"><stop class="ew0uim6gn"/><stop offset="1" class="cj7sibb8n"/></radialGradient><radialGradient id="is3aqpd" cx="0" cy="0" r="1" gradientTransform="rotate(54.14 3.403 17.438)scale(1.62703 6.22235)" gradientUnits="userSpaceOnUse"><stop class="ryea0ookf"/><stop offset="1" class="ko_af4_wq"/></radialGradient><radialGradient id="iE0NYnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72875 1.74927 -1.1218 -1.10864 19.052 5.169)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="w5pmvqbyv"/><stop offset="1" class="dw874cmcb"/></radialGradient><radialGradient id="iE8Q53b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.69922 1.10156 0 18.776 6.55)" gradientUnits="userSpaceOnUse"><stop class="a9by5rbfj"/><stop offset="1" class="p98xi8b4g"/></radialGradient><radialGradient id="ih56C1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90625 .92188 0 16.01 6.502)" gradientUnits="userSpaceOnUse"><stop class="d6gk4jb3c"/><stop offset="1" class="xv_mpdbhn"/></radialGradient><radialGradient id="id71Exe" cx="0" cy="0" r="1" gradientTransform="matrix(-.47656 0 0 -.14893 17.659 8.098)" gradientUnits="userSpaceOnUse"><stop class="ph4flqb3k"/><stop offset="1" class="h7fgkmbjb"/></radialGradient><radialGradient id="i0anx7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39263 1.04529 0 17.41 8.412)" gradientUnits="userSpaceOnUse"><stop class="ieyztivmt"/><stop offset="1" class="jkdewyb8l"/></radialGradient><radialGradient id="iBhIerD" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 7.726 8.384)scale(.55383 .87854)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="ijnnatW" cx="0" cy="0" r="1" gradientTransform="matrix(-.13647 -.17586 .24212 -.18789 18.565 6.904)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igrTQMc" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 6.437 7.707)scale(.55383 .87855)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iBXmUIt" cx="0" cy="0" r="1" gradientTransform="matrix(-.00455 -.29073 .34947 -.00547 15.95 6.984)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idPHgob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98437 1.60938 -.62216 -.76713 15.589 4.074)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="apmdt3x3q"/><stop offset=".77" class="s2wvo_jzf"/></radialGradient><radialGradient id="iYSVVzp" cx="0" cy="0" r="1" gradientTransform="rotate(141.561 9.308 4.683)scale(3.86999 4.98747)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="ciibtfg0w"/><stop offset=".961" class="nk2v8nx5g"/></radialGradient><radialGradient id="iNOPARb" cx="0" cy="0" r="1" gradientTransform="rotate(-77.784 11.852 -8.387)scale(3.10147 7.95485)" gradientUnits="userSpaceOnUse"><stop offset=".607" class="kc79u3bwy"/><stop offset="1" class="l0z7fbvsr"/></radialGradient><radialGradient id="i2R6tHe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53115 .06602 -.11185 -4.28845 18.218 3.633)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="mpjri6nek"/><stop offset="1" class="mfg0q5l4l"/></radialGradient><radialGradient id="iqQEroj" cx="0" cy="0" r="1" gradientTransform="rotate(-151.37 10.649 -.103)scale(1.4544 .9065)" gradientUnits="userSpaceOnUse"><stop class="wiiznx1ow"/><stop offset="1" class="owmsj2b8b"/></radialGradient><radialGradient id="iRkDUub" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.2422 -.5655 .09247 21.026 3.793)" gradientUnits="userSpaceOnUse"><stop class="mk_tesa_t"/><stop offset="1" class="hj78b9cjo"/></radialGradient><radialGradient id="icbotye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11657 .3125 -.09737 -.3479 22.346 4.668)" gradientUnits="userSpaceOnUse"><stop class="o5bua8boy"/><stop offset="1" class="rz_b8bbbi"/></radialGradient><radialGradient id="iaPXNua" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -1.38766 .70345 -.301 21.932 6.48)" gradientUnits="userSpaceOnUse"><stop class="o0h7y_boi"/><stop offset="1" class="s9ajizb_e"/></radialGradient><filter id="iUIqbRb" width="14.874" height="15.272" x="7.851" y="1.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.607843 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1300" result="effect2_innerShadow_4002_1300"/></filter><filter id="in5Mtyd" width="16.97" height="13.626" x="7.639" y="16.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1300" result="effect2_innerShadow_4002_1300"/></filter><filter id="izcwbKb" width="8.803" height="12.453" x="15.083" y="15.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".5"/></filter><filter id="iyecqow" width="1.41" height="1.949" x="24.485" y="7.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="ivFguie" width="20.634" height="10.708" x="5.683" y="7.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.458824 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="iROQBrz" width="11.112" height="3.615" x="10.829" y="25.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".2"/></filter><filter id="ihAV9Gd" width="3.297" height="3.17" x="8.245" y="23.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".2"/></filter><filter id="iY2BPwd" width="3.085" height="3.032" x="11.506" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".2"/></filter><filter id="id402Ib" width="6.547" height="2.797" x="14.14" y="13.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".125"/></filter><filter id="iDVlU7d" width="7.845" height="3.428" x="13.691" y="12.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.305882 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.388235 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1300" result="effect2_innerShadow_4002_1300"/></filter><filter id="iryLlCc" width="2.002" height="1.902" x="13.691" y="6.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="iIe32Jd" width="1.669" height="1.67" x="19.428" y="6.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".1"/></filter><filter id="iSjFUbd" width="1.47" height="1.47" x="13.918" y="6.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="iNaG9Td" width="6.422" height="6.428" x="14.399" y="4.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.65098 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="iAjqokc" width="1.609" height="2.085" x="16.51" y="6.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".125"/></filter><filter id="irUyIAd" width="2.152" height=".865" x="16.335" y="8.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".025"/></filter><filter id="iR7Hxei" width="1.855" height=".76" x="17.885" y="6.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="iFZvVsd" width="1.855" height=".76" x="15.08" y="6.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="i5Icotd" width="1.531" height=".726" x="15.16" y="5.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="itd3Iib" width="1.531" height=".727" x="18.361" y="5.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="i3E2sjd" width=".545" height=".492" x="18.225" y="6.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="i4hekNe" width=".689" height=".702" x="18.68" y="6.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".1"/></filter><filter id="i4PCvUb" width=".745" height=".777" x="16.055" y="6.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".1"/></filter><filter id="iBj1LqO" width=".62" height=".497" x="15.65" y="6.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="iZTZXee" width="1.231" height=".473" x="18.431" y="5.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="im4pBed" width="1.231" height=".473" x="15.21" y="5.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="i1Ov0jd" width="2.163" height="2.504" x="13.885" y="3.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="i8VuHPH" width="5.15" height="3.645" x="15.32" y="2.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.721569 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/><feGaussianBlur result="effect2_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="iCDnd6d" width="5.264" height="3.495" x="15.207" y="2.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".05"/></filter><filter id="ihtZ4Zc" width="3.17" height="3.061" x="19.276" y="3.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1300"/></filter><filter id="idd4qPd" width="2.055" height="6.641" x="24.354" y="7.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".25"/></filter><filter id="i1GfQze" width="4.719" height="3.595" x="19.998" y="10.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".25"/></filter><filter id="iRLQzid" width="1.175" height="2.326" x="23.635" y="7.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1300" stdDeviation=".125"/></filter><linearGradient id="iGVMdeX" x1="6.713" x2="7.026" y1="16.84" y2="16.84" gradientUnits="userSpaceOnUse"><stop class="ibfw5mfbi"/><stop offset="1" class="hmjg67bwx"/></linearGradient><linearGradient id="iXwwCbc" x1="8.135" x2="14.729" y1="16.559" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="j_5121a2j"/><stop offset="1" class="yyfnq7-ce"/></linearGradient><linearGradient id="iA61mHd" x1="17.354" x2="17.354" y1="18.028" y2="16.371" gradientUnits="userSpaceOnUse"><stop offset=".113" class="e06i83y_w"/><stop offset="1" class="lm6_gh6zl"/></linearGradient><linearGradient id="iOPfD1b" x1="11.768" x2="20.875" y1="26.957" y2="28.8" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iBoQFCd" x1="10.518" x2="8.203" y1="25.75" y2="25.377" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="i7Use1c" x1="14.012" x2="13.482" y1="24.087" y2="26.197" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iSzPwib" x1="14.05" x2="14.641" y1="6.934" y2="8.159" gradientUnits="userSpaceOnUse"><stop class="c3abnuf9m"/><stop offset="1" class="ilhfq-rgs"/></linearGradient><linearGradient id="ikemhme" x1="17.838" x2="17.37" y1="7.754" y2="7.778" gradientUnits="userSpaceOnUse"><stop class="bjtjc7yte"/><stop offset="1" class="uoi807b3e"/></linearGradient><linearGradient id="i6Un3wd" x1="17.452" x2="17.452" y1="8.442" y2="8.262" gradientUnits="userSpaceOnUse"><stop offset="0" class="p8im66f_y"/><stop offset="1" class="qq2gex10o"/></linearGradient><linearGradient id="i9jLwvb" x1="17.41" x2="17.41" y1="6.828" y2="7.762" gradientUnits="userSpaceOnUse"><stop class="iy-8e7b5c"/><stop offset=".824" class="io9zrqs7f"/></linearGradient><linearGradient id="iarC7eu" x1="16.98" x2="17.247" y1="9.34" y2="8.825" gradientUnits="userSpaceOnUse"><stop class="off1fssuq"/><stop offset="1" class="g4i014bsv"/></linearGradient><linearGradient id="ijtHQge" x1="19.158" x2="18.974" y1="6.886" y2="7" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8APABb" x1="16.559" x2="16.375" y1="6.886" y2="7" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXvc2gd" x1="24.421" x2="26.951" y1="10.074" y2="11.145" gradientUnits="userSpaceOnUse"><stop class="l76_zob2i"/><stop offset="1" class="xfc8esbzj"/></linearGradient><linearGradient id="i2B994k" x1="23.06" x2="23.438" y1="13.184" y2="11.179" gradientUnits="userSpaceOnUse"><stop class="bb3f-2uap"/><stop offset="1" class="ccv1u1olv"/></linearGradient><linearGradient id="iDalP4O" x1="24.213" x2="24.213" y1="9.278" y2="6.653" gradientUnits="userSpaceOnUse"><stop class="t06aabcnd"/><stop offset="1" class="ut2o6sbat"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-merpeople-medium-light" /></template>
<style>
.a4m3534rg {
  stop-color: var(--svg-color--ecb597, #ECB597);
}

.a680lr2dp {
  stop-color: var(--svg-color--d19579, #D19579);
}

.a9by5rbfj {
  stop-color: var(--svg-color--ca9281, #CA9281);
}

.aa79y-bxe {
  stop-color: var(--svg-color--c48969, #C48969);
}

.apmdt3x3q {
  stop-color: var(--svg-color--f6dbaa, #F6DBAA);
}

.azzh1940u {
  stop-color: var(--svg-color--daa28a, #DAA28A);
}

.b9vbofbwl {
  d: path("M14.653 7.843a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.bb3f-2uap {
  stop-color: var(--svg-color--e7b496, #E7B496);
}

.bizlpnzzl {
  cx: 15.959px;
  cy: 6.798px;
  rx: 0.229px;
  ry: 0.116px;
}

.bjtjc7yte {
  stop-color: var(--svg-color--e9b89b, #E9B89B);
}

.bkzx2xbnc {
  stop-color: var(--svg-color--c78b70, #C78B70);
  stop-opacity: 0;
}

.c3abnuf9m {
  stop-color: var(--svg-color--c9907a, #C9907A);
}

.ccv1u1olv {
  stop-color: var(--svg-color--e7b496, #E7B496);
  stop-opacity: 0;
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.ciibtfg0w {
  stop-color: var(--svg-color--fff3bd, #FFF3BD);
}

.cj7sibb8n {
  stop-color: var(--svg-color--b4897a, #B4897A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.csx3pkbqc {
  d: path("M19.17 7.03a.5.5 0 0 0-.137-.272l-.152.168l.069.134z");
}

.d08nthbva {
  stop-color: var(--svg-color--ac7687, #AC7687);
}

.d6gk4jb3c {
  stop-color: var(--svg-color--cb8e81, #CB8E81);
}

.dbc20iija {
  stop-color: var(--svg-color--b97675, #B97675);
}

.dfd63o21n {
  fill: var(--svg-color--000, #000);
  d: path("M18.399 7.1a.3.3 0 0 1 .302-.301a.3.3 0 0 1 .269.44h-.535a.3.3 0 0 1-.036-.138");
}

.dw874cmcb {
  stop-color: var(--svg-color--d19d8b, #D19D8B);
  stop-opacity: 0;
}

.dx7rnx6ra {
  fill: var(--svg-color--8c592c, #8C592C);
  d: path("m15.402 6.157l-.002.002a.159.159 0 0 1-.163-.272l.002-.002l.006-.003l.02-.01q.024-.014.068-.035a2 2 0 0 1 .242-.096c.201-.064.482-.118.785-.064a.158.158 0 0 1-.055.312c-.236-.042-.462 0-.633.054a1.6 1.6 0 0 0-.257.107z");
}

.e06i83y_w {
  stop-color: var(--svg-color--d5a08c, #D5A08C);
}

.e33ktg_du {
  d: path("M17.054 2.585c-.67-.148-1.677.592-1.747.84c1.238 2.024 2.254 1.994 3.955 1.93c.945-.036 1.02.3 1.1.505c.156-2.688-1.783-2.938-3.308-3.275");
}

.e62kxsb4l {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M17.41 8.929a1.8 1.8 0 0 1-.84-.204c-.083-.043-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.173-.12-.13a1.8 1.8 0 0 1-.84.204");
}

.e7jbu0blg {
  d: path("M14.09 13.137a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3v-1.128a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.063-.18.063-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.efontmzot {
  d: path("M16.6 7.037c0-.17-.138-.283-.175-.317l-.17.164l.104.213z");
}

.ew0uim6gn {
  stop-color: var(--svg-color--b4897a, #B4897A);
}

.ewg_wtbvw {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.736 6.872c-.157-.276-.396-.494-.909-.494a.98.98 0 0 0-.634.218c-.159.128-.137.292-.014.354l.328.188c.385-.125.811-.142 1.229-.266");
}

.fs81_6bpu {
  stop-color: var(--svg-color--e8b492, #E8B492);
}

.ft5dv1b6b {
  fill: none;
}

.fzv28epeh {
  stop-color: var(--svg-color--dcca95, #DCCA95);
  stop-opacity: 0;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g4i014bsv {
  stop-color: var(--svg-color--ce978b, #CE978B);
  stop-opacity: 0;
}

.ga8awzqfa {
  stop-color: var(--svg-color--e5b79c, #E5B79C);
}

.gg7v2sgvk {
  d: path("M20.726 13.675v3.421a.65.65 0 0 1-.65.65H14.75a.65.65 0 0 1-.65-.65v-2.75l-1.953 1.698a2.5 2.5 0 0 1-1.64.613h-1.84l-.612.526a.527.527 0 0 1-.716-.774l.317-.315a.1.1 0 0 0-.019-.155l-.018-.01a.384.384 0 0 0-.476.064l-.554.583a.526.526 0 0 1-.776-.71l.755-.857a.98.98 0 0 1 .621-.325l3.069-.356a.5.5 0 0 0 .284-.132l3.247-3.04c.889-.889 2.57-.98 3.735-.98c1.495 0 2.532.234 3.2.574l2.862 1.473a.202.202 0 0 0 .293-.16c.049-.5.132-1.271.197-1.853a.2.2 0 0 0-.046-.15l-.373-.445a1 1 0 0 1-.235-.644V7.77a.531.531 0 0 1 1.062 0v.667c0 .18.045.36.17.488c.065.067.145.138.239.2c.116.078.255-.016.255-.156v-.5a.531.531 0 1 1 1.063 0v1.39l.015.703c.019.846.042 1.907.088 2.883c.03.64-.263 1.255-.79 1.618a1.8 1.8 0 0 1-1.84.122z");
}

.glz-c5bvr {
  stop-color: var(--svg-color--9f5d42, #9F5D42);
}

.gn_qypbgw {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.078c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.296a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.723c-.062-1.813-1.562-2.516-2.57-3.149c-.523-.328-2.055-1.144-2.055-2.926");
}

.gpjj60boc {
  stop-color: var(--svg-color--ad6e77, #AD6E77);
}

.grlhkzb5c {
  stop-color: var(--svg-color--bd835a, #BD835A);
}

.gu1n7hb8i {
  stop-color: var(--svg-color--ca8e77, #CA8E77);
  stop-opacity: 0;
}

.gwqfskb8v {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
}

.h7fgkmbjb {
  stop-color: var(--svg-color--e6b49a, #E6B49A);
  stop-opacity: 0;
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hilc70b9p {
  stop-color: var(--svg-color--c68e7d, #C68E7D);
}

.hj78b9cjo {
  stop-color: var(--svg-color--34affa, #34AFFA);
  stop-opacity: 0;
}

.hmjg67bwx {
  stop-color: var(--svg-color--bf7f6c, #BF7F6C);
  stop-opacity: 0;
}

.i736akkjc {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.997 6.413a.825.825 0 0 0-.8.625a.162.162 0 0 0 .158.202h1.318a.136.136 0 0 0 .135-.161a.83.83 0 0 0-.81-.666");
}

.ibfw5mfbi {
  stop-color: var(--svg-color--dfa78e, #DFA78E);
}

.ieyztivmt {
  stop-color: var(--svg-color--ca8c85, #CA8C85);
}

.iibz_cc8h {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.41 8.929a1.8 1.8 0 0 1-.84-.204c-.083-.043-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.173-.12-.13a1.8 1.8 0 0 1-.84.204Z");
}

.ilhfq-rgs {
  stop-color: var(--svg-color--c28177, #C28177);
}

.io9zrqs7f {
  stop-color: var(--svg-color--d9a389, #D9A389);
  stop-opacity: 0;
}

.itk8q2bqv {
  d: path("M13.356 19.078c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.296a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.723c-.062-1.813-1.562-2.516-2.57-3.149c-.523-.328-2.055-1.144-2.055-2.926");
}

.iy-8e7b5c {
  stop-color: var(--svg-color--d9a389, #D9A389);
}

.j_5121a2j {
  stop-color: var(--svg-color--dda88c, #DDA88C);
}

.j-y2d-bpp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.085 6.872c.157-.276.396-.494.909-.494a.98.98 0 0 1 .634.218c.159.128.137.292.014.354l-.328.188c-.385-.125-.811-.142-1.229-.266");
}

.j391rbtek {
  stop-color: var(--svg-color--d29886, #D29886);
}

.jekb5o0nb {
  stop-color: var(--svg-color--d59e8c, #D59E8C);
}

.jkdewyb8l {
  stop-color: var(--svg-color--ca8c85, #CA8C85);
  stop-opacity: 0;
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jl_5q555j {
  d: path("M25.683 7.938h-.003a.53.53 0 0 0-.531.531v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.128-.17-.308-.17-.488v-.546l.56-.558a.44.44 0 0 1 .638.605");
}

.jpih75bxh {
  stop-color: var(--svg-color--c78b70, #C78B70);
}

.js8y_db3g {
  stop-color: var(--svg-color--c48581, #C48581);
  stop-opacity: 0;
}

.kawgt3bsr {
  stop-color: var(--svg-color--e0a37b, #E0A37B);
}

.kc79u3bwy {
  stop-color: var(--svg-color--ddcd98, #DDCD98);
  stop-opacity: 0;
}

.knj7mgbph {
  stop-color: var(--svg-color--c48969, #C48969);
  stop-opacity: 0;
}

.ko_af4_wq {
  stop-color: var(--svg-color--cd9178, #CD9178);
  stop-opacity: 0;
}

.krhwxbssl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.66 6.685c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.144.093-.21c.089-.067.191-.08.229-.03");
}

.ktg8q2baj {
  d: path("M18.66 6.685c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.144.093-.21c.089-.067.191-.08.229-.03");
}

.kx-u1f1nr {
  d: path("M20.263 7.843a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.l0z7fbvsr {
  stop-color: var(--svg-color--ddcd98, #DDCD98);
}

.l336a0pec {
  stop-color: var(--svg-color--daa28a, #DAA28A);
  stop-opacity: 0;
}

.l76_zob2i {
  stop-color: var(--svg-color--ecba9b, #ECBA9B);
}

.lhvnpmb3c {
  d: path("M16.12 6.573a.527.527 0 0 0-.508.667h1.018a.53.53 0 0 0-.51-.666");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm6_gh6zl {
  stop-color: var(--svg-color--d5a08c, #D5A08C);
  stop-opacity: 0;
}

.lyd9g1b-v {
  stroke: var(--svg-color--8e5f38, #8E5F38);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M18.557 5.806c.19-.047.664-.023.981.203");
}

.m62n6lejs {
  stop-color: var(--svg-color--e5a785, #E5A785);
  stop-opacity: 0;
}

.m7l8ktb_c {
  d: path("M17.054 2.585c-.67-.148-1.564.585-1.633.833c.91 2.14 2.14 2.001 3.841 1.937c.945-.036 1.02.3 1.1.505c.156-2.688-1.783-2.939-3.308-3.275");
}

.mfg0q5l4l {
  stop-color: var(--svg-color--f5dda4, #F5DDA4);
}

.mk_tesa_t {
  stop-color: var(--svg-color--49c4fa, #49C4FA);
}

.mmf02ltsv {
  stop-color: var(--svg-color--cc937c, #CC937C);
}

.mpjri6nek {
  stop-color: var(--svg-color--f5dda4, #F5DDA4);
  stop-opacity: 0;
}

.mz6q3lszi {
  d: path("M25.054 9.544c.399-.066.488-.33.488-.5v-.536a.184.184 0 1 1 .367 0v4.93a.527.527 0 1 1-1.055 0v-3.68c0-.11.09-.196.2-.214");
}

.n02h-lbzo {
  stop-color: var(--svg-color--ac7687, #AC7687);
  stop-opacity: 0;
}

.n4lm9l72r {
  stop-color: var(--svg-color--ac757f, #AC757F);
}

.n6mjte-pr {
  d: path("m17.184 6.995l-.314 1.004a.32.32 0 0 0 .308.413h.465A.32.32 0 0 0 17.95 8l-.314-1.004c-.067-.223-.381-.223-.452 0");
}

.n7-hw2b3h {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
  stop-opacity: 0;
}

.ngxjebrpy {
  fill: var(--svg-color--000, #000);
  d: path("M16.422 7.1a.3.3 0 0 0-.302-.301a.3.3 0 0 0-.269.44h.535a.3.3 0 0 0 .036-.138");
}

.nk2v8nx5g {
  stop-color: var(--svg-color--f2d3a5, #F2D3A5);
}

.nxfagccjp {
  fill: var(--svg-color--daa587, #DAA587);
  d: path("m17.184 6.995l-.314 1.004a.32.32 0 0 0 .308.413h.465A.32.32 0 0 0 17.95 8l-.314-1.004c-.067-.223-.381-.223-.452 0");
}

.o0h7y_boi {
  stop-color: var(--svg-color--45beff, #45BEFF);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.obylexqck {
  stop-color: var(--svg-color--bb8264, #BB8264);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.off1fssuq {
  stop-color: var(--svg-color--ce978b, #CE978B);
}

.ok0xogb6i {
  stop-color: var(--svg-color--d39b83, #D39B83);
}

.ols1i2kaq {
  stop-color: var(--svg-color--e9ac8f, #E9AC8F);
}

.ookdrzgqt {
  stop-color: var(--svg-color--8451b2, #8451B2);
}

.opga4-hbt {
  d: path("m21.018 3.778l.204.627c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.659c.03-.1 0-.2-.08-.26l-.539-.398c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.647c.07-.23.325-.21.395 0");
}

.otc9m4bci {
  stop-color: var(--svg-color--cc937c, #CC937C);
  stop-opacity: 0;
}

.owmsj2b8b {
  stop-color: var(--svg-color--ddcc9f, #DDCC9F);
  stop-opacity: 0;
}

.p-43r8bct {
  d: path("M6.762 16.03a.486.486 0 0 1 .973 0v.774a.486.486 0 0 1-.973 0z");
}

.p8im66f_y {
  stop-color: var(--svg-color--bb7b77, #BB7B77);
}

.p98xi8b4g {
  stop-color: var(--svg-color--ca9281, #CA9281);
  stop-opacity: 0;
}

.pgp143bck {
  d: path("M14.641 8.159a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.ph4flqb3k {
  stop-color: var(--svg-color--e6b49a, #E6B49A);
}

.pk4gvbx0m {
  stroke: var(--svg-color--8e5f38, #8E5F38);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.316 5.806c-.19-.047-.664-.023-.981.203");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pquvpov8y {
  stop-color: var(--svg-color--fff8ba, #FFF8BA);
}

.pvvyv9bsi {
  d: path("M14.404 6.462h.007l-.006-.157l-.006-.181c.012-.56.34-.778.479-.85l.03-.012l.03-.012c.316-.145.57-.398.704-.73l.048-.114a.156.156 0 0 1 .273-.03a2.28 2.28 0 0 0 1.885.988h1.902c.107 0 .64.052.672.788l-.07 1.816c-.073 1.656-1.367 2.768-2.945 2.768c-1.58 0-2.872-1.112-2.945-2.768z");
}

.q13sv5b2f {
  d: path("M24.218 13.283v.793l-3.72-2.397l.083-.198z");
}

.qpsqlesux {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.416c.41.162 1.402.783 2.097 1.97");
}

.qq2gex10o {
  stop-color: var(--svg-color--c98b81, #C98B81);
  stop-opacity: 0;
}

.r1waaobic {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M24.085 7.617v1.248c0 .066.026.13.073.177l.26.26");
}

.r7vltcbae {
  stop-color: var(--svg-color--bb7d5e, #BB7D5E);
}

.rau17bcwj {
  stop-color: var(--svg-color--c78a84, #C78A84);
  stop-opacity: 0;
}

.rd_1vj1uu {
  stop-color: var(--svg-color--9971db, #9971DB);
}

.rl7em7bjk {
  stop-color: var(--svg-color--e5c199, #E5C199);
  stop-opacity: 0;
}

.ryea0ookf {
  stop-color: var(--svg-color--b77351, #B77351);
}

.ryny_ubjw {
  stop-color: var(--svg-color--d9a28a, #D9A28A);
  stop-opacity: 0;
}

.rz_b8bbbi {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
  stop-opacity: 0;
}

.s1hry0blp {
  stop-color: var(--svg-color--c5887d, #C5887D);
  stop-opacity: 0;
}

.s2wvo_jzf {
  stop-color: var(--svg-color--f6dbaa, #F6DBAA);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s727t-8_q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.897c-.307.353-1.133 1.101-1.885 1.832");
}

.s9ajizb_e {
  stop-color: var(--svg-color--45beff, #45BEFF);
  stop-opacity: 0;
}

.sc9s-1bed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.851c-.007.65.436 1.949 2.266 1.949h3.177c1.01-.014 3.316-.517 4.469-2.415");
}

.shpp5nbho {
  stop-color: var(--svg-color--be7f64, #BE7F64);
}

.sidjyzc1j {
  d: path("M18.701 6.573a.527.527 0 0 1 .508.667H18.19a.53.53 0 0 1 .51-.666");
}

.sn41dmbim {
  stop-color: var(--svg-color--c38575, #C38575);
}

.st4hs763z {
  stop-color: var(--svg-color--e5c199, #E5C199);
}

.t06aabcnd {
  stop-color: var(--svg-color--e5b799, #E5B799);
}

.t8zak5bmc {
  fill: var(--svg-color--8c592c, #8C592C);
  fill-rule: evenodd;
  d: path("m19.615 5.887l-.081.136za.159.159 0 0 1-.162.272l-.003-.002l-.067-.034a2 2 0 0 0-.202-.08a1.34 1.34 0 0 0-.634-.054a.159.159 0 0 1-.055-.312c.303-.054.584 0 .785.064a2 2 0 0 1 .33.141l.006.003z");
}

.tgd5bcc3y {
  stop-color: var(--svg-color--e0a37b, #E0A37B);
  stop-opacity: 0;
}

.tl-riq-5r {
  stop-color: var(--svg-color--e6bb9c, #E6BB9C);
}

.tlvzcsbls {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.824 6.413c.385 0 .711.266.8.625a.162.162 0 0 1-.158.202h-1.319a.136.136 0 0 1-.134-.161a.826.826 0 0 1 .81-.666");
}

.tylzkc2ni {
  d: path("M9.862 15.733c1.812 1.572 4.203 1.211 5.172.873V11.99h7.234c.517-1.324.156-2.448-.236-3.061a.28.28 0 0 1-.03-.24c.083-.235.193-.614.207-.914c.032-.66-.171-.706-.19-1.61c-.02-.905-.308-1.24-.782-2.013c-.383-.624-1.371-1.029-1.973-1.267c-.66-.261-.894-.757-1.89-.757c-.77 0-1.277.39-1.626.728a.85.85 0 0 1-.48.23c-1.223.163-2.266.734-2.844 1.8c-.338.624-.368 1.605-.364 2.277a.53.53 0 0 1-.421.513c-1.528.344-2.65 1.227-3.18 2.228c-.578 1.092-.863 3.864 1.403 5.83");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uies7db_y {
  fill: var(--svg-color--8c60d5, #8C60D5);
  d: path("M14.09 13.137a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3v-1.128a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.063-.18.063-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.uoi807b3e {
  stop-color: var(--svg-color--e9b89b, #E9B89B);
  stop-opacity: 0;
}

.ut2o6sbat {
  stop-color: var(--svg-color--e5b799, #E5B799);
  stop-opacity: 0;
}

.v8-b80bcd {
  stop-color: var(--svg-color--c68e7d, #C68E7D);
  stop-opacity: 0;
}

.vopejgz3x {
  stop-color: var(--svg-color--bd806d, #BD806D);
}

.vrorbj-kg {
  fill: var(--svg-color--b37572, #B37572);
  d: path("M14.715 13.825a.325.325 0 0 0-.325.324v.917c0 .583.473 1.055 1.056 1.055h3.935c.583 0 1.055-.472 1.055-1.055v-.917a.325.325 0 0 0-.324-.324h-1.496c-.501 0-.932.302-1.119.734c-.022.05-.146.05-.168 0a1.22 1.22 0 0 0-1.118-.734z");
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w1evdl1rb {
  cx: 15.959px;
  cy: 6.798px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.229px;
  ry: 0.116px;
}

.w4wjacb9v {
  stop-color: var(--svg-color--8c60d5, #8C60D5);
  stop-opacity: 0;
}

.w5pmvqbyv {
  stop-color: var(--svg-color--d19d8b, #D19D8B);
}

.wcbv0nbwv {
  stop-color: var(--svg-color--bd827e, #BD827E);
  stop-opacity: 0;
}

.wiiznx1ow {
  stop-color: var(--svg-color--ddcc9f, #DDCC9F);
}

.xbk-y3bqk {
  fill: var(--svg-color--c7887f, #C7887F);
  d: path("m17.179 7.076l-.404 1.005a.32.32 0 0 0 .307.413h.465a.32.32 0 0 0 .308-.413l-.314-1.005c-.068-.222-.292-.222-.363 0");
}

.xfc8esbzj {
  stop-color: var(--svg-color--ecba9b, #ECBA9B);
  stop-opacity: 0;
}

.xu7iftcsg {
  d: path("M20.263 8.159a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.xv_mpdbhn {
  stop-color: var(--svg-color--cb8e81, #CB8E81);
  stop-opacity: 0;
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y0a-8tbvz {
  stop-color: var(--svg-color--d9a28a, #D9A28A);
}

.ye462pblv {
  fill: var(--svg-color--33aef9, #33AEF9);
  d: path("m21.018 3.778l.204.627c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.659c.03-.1 0-.2-.08-.26l-.539-.398c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.647c.07-.23.325-.21.395 0");
}

.yiq9sac5t {
  stop-color: var(--svg-color--cf9981, #CF9981);
}

.ynngk8bxm {
  stop-color: var(--svg-color--c5887d, #C5887D);
}

.yvpamkx_l {
  stop-color: var(--svg-color--ad664d, #AD664D);
}

.yyfnq7-ce {
  stop-color: var(--svg-color--dda88c, #DDA88C);
  stop-opacity: 0;
}

.z1wxhzofg {
  d: path("M15.62 4.543c-.22.565-1.18 1.029-1.61 1.14c-.142-1.142.301-2.522 1.702-2.273l.236.914c-.236-.066-.286.11-.328.22");
}

.zfvcixbyw {
  stop-color: var(--svg-color--d39f87, #D39F87);
}

.zku_rzyyo {
  stop-color: var(--svg-color--8d61d6, #8D61D6);
  stop-opacity: 0;
}

.zn1rvob2u {
  stop-color: var(--svg-color--dcca95, #DCCA95);
}

.zshz1kb8t {
  stop-color: var(--svg-color--ac757f, #AC757F);
  stop-opacity: 0;
}

.ztn7pxbjf {
  stop-color: var(--svg-color--a86367, #A86367);
}

.zvht3bbsb {
  d: path("M21.317 26.653c0-5.344-3.922-7.97-5.234-9l3.25-1.453c1.125.52 3.035 2.357 3.453 5.109c.484 3.187-.927 4.927-1.469 5.344");
}

</style>
