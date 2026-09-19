<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipFTeUd)" class="h-jczlzen"/><path fill="url(#iN3vord)" class="ze-agacxi"/><rect fill="url(#ik8ktme)" class="gyc1lm0xs"/><g filter="url(#iM9oXbd)"><path fill="url(#iDWmsYv)" class="fsxm9dwni"/><path fill="url(#ih1a0Mc)" class="fsxm9dwni"/><path fill="url(#iJrxi6c)" class="fsxm9dwni"/><path fill="url(#ig1h4Ub)" class="fsxm9dwni"/><path fill="url(#iMqNrec)" class="fsxm9dwni"/></g><path fill="url(#iue2uzK)" class="fsxm9dwni"/><path fill="url(#i5SWnpb)" class="fsxm9dwni"/><path fill="url(#iMFwBSb)" class="fsxm9dwni"/><g filter="url(#i3rNQad)"><path class="di5jaebmp"/></g><g filter="url(#inW0V3b)"><path class="xuzndv0cv"/><path fill="url(#iSvsX2d)" class="h9nb3dbmm"/><path fill="url(#iq2eBtz)" class="h9nb3dbmm"/><path fill="url(#iku51Tc)" class="h9nb3dbmm"/><path fill="url(#iOo0yQe)" class="h9nb3dbmm"/></g><g filter="url(#iFWrwWd)"><path fill="url(#iXsW89c)" class="fk9nbx4th"/><path fill="url(#i66V8Yb)" class="fk9nbx4th"/><path fill="url(#iUJqoVb)" class="fk9nbx4th"/></g><path fill="url(#i37Ptac)" class="fk9nbx4th"/><path fill="url(#iAV8gtT)" class="fk9nbx4th"/><g filter="url(#iRK2Gte)"><path class="n2xzttb7n"/><path fill="url(#iFb5T5d)" class="dqa_-7bzp"/><path fill="url(#ivSyzDd)" class="dqa_-7bzp"/></g><g filter="url(#ixbjzMc)"><path class="fbkqlsb6l"/><path fill="url(#ic8qiZb)" class="sx2208btj"/></g><path class="wiieli2ej"/><path fill="url(#iGoekNb)" class="hi0vjzatb"/><path class="dain57iqy"/><g filter="url(#ix8rxUc)"><path class="mxpallb1y"/><path fill="url(#iSDDtpb)" class="d879qkbvi"/></g><g filter="url(#im31bwc)"><path fill="url(#ivuPxEJ)" class="gfer3rbfb"/></g><path class="hwvoaqesi"/><path fill="url(#ieU5R2d)" class="wu2h8jb4k"/><path class="uaxsyh7oh"/><g filter="url(#iX2FFmd)"><path fill="url(#iqDZooO)" class="afwn1lnfh"/></g><g filter="url(#ibDUHEN)"><ellipse transform="rotate(-27.914 13.272 14.777)" class="lulnx3bbe"/><ellipse fill="url(#i9ZqFNd)" transform="rotate(-27.914 13.272 14.777)" class="f0qoe92_d"/></g><path fill="url(#iS9jZSb)" class="ppk0kktky"/><path fill="url(#ipicDre)" class="nrnvctv1v"/><g filter="url(#iE1fIqe)"><path fill="url(#ieMT60d)" class="ygjg_lb-n"/></g><g filter="url(#i46ikwj)"><path fill="url(#i0vIgNe)" class="fv_h9xbci"/></g><g filter="url(#i5H1gFd)"><path clip-rule="evenodd" class="vtzl6jmuj"/></g><g filter="url(#iCWh7lc)"><path stroke="url(#imeLlBe)" class="dg217h9if"/></g><g filter="url(#iGb8Vae)"><path clip-rule="evenodd" class="nq6rqyi_k"/></g><g filter="url(#igq1Bwe)"><path stroke="url(#ify8Wza)" class="bxh6ncchi"/></g><path stroke="url(#iJIb9je)" class="a-yl-3btr"/><path fill="url(#iiyPxme)" class="i-377o6ky"/><path fill="url(#ib71Hqe)" class="i-377o6ky"/><path fill="url(#in5utCd)" class="i-377o6ky"/><path fill="url(#ianvqSH)" class="i-377o6ky"/><path fill="url(#iOAhnad)" class="i-377o6ky"/><path fill="url(#i50HDKe)" class="i-377o6ky"/><path fill="url(#ifC2ncc)" class="i-377o6ky"/><path fill="url(#iJj6fAb)" class="i-377o6ky"/><path fill="url(#iT1p4BP)" class="i-377o6ky"/><path fill="url(#izkTnEb)" class="i-377o6ky"/><path fill="url(#iVfic0d)" class="i-377o6ky"/><path fill="url(#im8Z1uc)" class="i-377o6ky"/><path fill="url(#icHg3Rj)" class="dges7ib9m"/><path fill="url(#ictyttc)" class="dges7ib9m"/><path fill="url(#i4olntC)" class="vtekkxd_w"/><path fill="url(#ipIrvKd)" class="vtekkxd_w"/><path fill="url(#iu6jDXd)" class="vtekkxd_w"/><path fill="url(#iQaNNAd)" class="cb1ljub6x"/><path fill="url(#iIcKf0d)" class="cb1ljub6x"/><path fill="url(#idOfR2I)" class="rrphcb4zv"/><path fill="url(#it5JL3d)" class="rrphcb4zv"/><g filter="url(#iy2QBnn)"><path fill="url(#itGO1it)" class="bf8qmd23r"/></g><g filter="url(#iCLqomc)"><path stroke="url(#i6X8AKd)" class="eusvtmb2r"/></g><path stroke="url(#iga8YZd)" class="v61f_wbit"/><path stroke="url(#iHSnOIb)" class="v61f_wbit"/><path stroke="url(#imegOtd)" class="v61f_wbit"/><path class="nax04kucn"/><path stroke="url(#iiFiDbc)" class="nh2kw4_uc"/><path stroke="url(#iLoVxkd)" class="nh2kw4_uc"/><path stroke="url(#im6WHLd)" class="d8ptwz9tw"/><path stroke="url(#iapKp5d)" class="d8ptwz9tw"/><path stroke="url(#iJeulZd)" class="d8ptwz9tw"/><path class="sdjfhcbou"/><path stroke="url(#iPB1SIb)" class="dbid5acei"/><path stroke="url(#iwgROoe)" class="dbid5acei"/><path stroke="url(#i4Sz9jc)" class="jx3zfg-wy"/><path stroke="url(#iaI6Bab)" class="jx3zfg-wy"/><path stroke="url(#isyjyZj)" class="jx3zfg-wy"/><path class="ywm5k41wv"/><path stroke="url(#iUAWlct)" class="gg4pweb1t"/><path stroke="url(#i7yjFid)" class="gg4pweb1t"/><path stroke="url(#ivhKXJc)" class="ipg0cn99k"/><path stroke="url(#iPt7U6c)" class="ipg0cn99k"/><path stroke="url(#igtd1lb)" class="ipg0cn99k"/><path class="fjyqc_bny"/><path stroke="url(#iv8VgJe)" class="u-qvctb2c"/><path stroke="url(#ik3Vzxb)" class="u-qvctb2c"/><path fill="url(#igteJrc)" class="uz3hg9bsf"/><path fill="url(#iIQDn4c)" class="igo7pk_ym"/><path fill="url(#iPBFoce)" class="igo7pk_ym"/><g filter="url(#ixrIoeb)"><path stroke="url(#ijecnMc)" class="fohmhtbju"/></g><g filter="url(#iH43H2b)"><path stroke="url(#ir4u4PN)" class="nh7q47k8r"/></g><g filter="url(#iwMZRse)"><path stroke="url(#iG8IWhG)" class="vxljdps-k"/></g><g filter="url(#i8fPqcd)"><path stroke="url(#i3fCmqc)" class="wgy-qlbik"/></g><defs><radialGradient id="ipFTeUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 21.983 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="ezh02gbvd"/><stop offset=".837" class="gavknk-rw"/></radialGradient><radialGradient id="iN3vord" cx="0" cy="0" r="1" gradientTransform="matrix(1.12646 -.03884 .11746 3.40643 9.608 18.052)" gradientUnits="userSpaceOnUse"><stop class="okxecjbze"/><stop offset=".944" class="khto69bzj"/></radialGradient><radialGradient id="ik8ktme" cx="0" cy="0" r="1" gradientTransform="matrix(2.9129 2.71352 -4.0321 4.32836 14.9 21.859)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="t399fcb5k"/><stop offset="1" class="vxpddkamp"/></radialGradient><radialGradient id="iDWmsYv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5625 0 0 -6.92232 18.625 16.476)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="j2u72qbdb"/><stop offset=".637" class="nu0bve_mm"/></radialGradient><radialGradient id="ih1a0Mc" cx="0" cy="0" r="1" gradientTransform="rotate(105.939 5.022 11.943)scale(4.69997 4.25479)" gradientUnits="userSpaceOnUse"><stop class="q3305mbzy"/><stop offset="1" class="uj-nym00r"/></radialGradient><radialGradient id="iJrxi6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82288 1.78838 0 13.579 14.35)" gradientUnits="userSpaceOnUse"><stop offset=".009" class="f4ksqbb1r"/><stop offset="1" class="jt8x2h0ur"/></radialGradient><radialGradient id="ig1h4Ub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34636 1.59055 0 18.488 14.149)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="ql2vfvfmz"/><stop offset="1" class="a9n1f6bpa"/></radialGradient><radialGradient id="iMqNrec" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -3.96846 7.80799 .86077 13.75 22.443)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="ezip59b9l"/><stop offset="1" class="lsgwilbat"/></radialGradient><radialGradient id="i5SWnpb" cx="0" cy="0" r="1" gradientTransform="rotate(60.555 -1.23 14.703)scale(3.35069 6.6748)" gradientUnits="userSpaceOnUse"><stop class="qsgc35tqu"/><stop offset="1" class="mlgnx_bnj"/></radialGradient><radialGradient id="iMFwBSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9417 -2.80617 .70622 .48866 10.227 11.813)" gradientUnits="userSpaceOnUse"><stop class="vaqwmfbyh"/><stop offset="1" class="bykdelbyf"/></radialGradient><radialGradient id="iku51Tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23468 -.91915 0 16.384 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="icf7hpmps"/><stop offset="1" class="y2a69ng6x"/></radialGradient><radialGradient id="i66V8Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.69214 5.50698 0 16.105 10.37)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="wgttxsdys"/><stop offset="1" class="rotm0lbjl"/></radialGradient><radialGradient id="iUJqoVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 1.22339 -2.53932 3.50266 9.605 9.147)" gradientUnits="userSpaceOnUse"><stop class="elwg_hb8v"/><stop offset="1" class="x-kyklb-a"/></radialGradient><radialGradient id="i37Ptac" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.34375 3.84014 .40961 9.845 14.1)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="kg5wfpbcx"/><stop offset="1" class="lfjjhubys"/></radialGradient><radialGradient id="iAV8gtT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18953 1.36893 -2.21408 -1.92393 20.799 8.236)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="qy05b9bsw"/><stop offset="1" class="aqwz8eb5i"/></radialGradient><radialGradient id="iFb5T5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70756 0 0 -.70728 16.54 7.8)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="wx87iwb8j"/><stop offset="1" class="ew05122nr"/></radialGradient><radialGradient id="ivSyzDd" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.03 12.188)" gradientUnits="userSpaceOnUse"><stop class="bo9ofmw9k"/><stop offset=".288" class="tpx6wbcio"/></radialGradient><radialGradient id="ic8qiZb" cx="0" cy="0" r="1" gradientTransform="matrix(3.3199 .93338 -.3858 1.37221 18.934 8.656)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="oju6c_bmm"/><stop offset="1" class="t39rzsbyn"/></radialGradient><radialGradient id="iGoekNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.319 14.882)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="iSDDtpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.07 14.973)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieU5R2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.567 14.882)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="i9ZqFNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.256 15.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS9jZSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42879 0 0 1.59032 21.416 15.335)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="y895atbwd"/><stop offset="1" class="p0trpqw-l"/></radialGradient><radialGradient id="ipicDre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51123 -.03147 .03945 -1.89453 10.447 15.608)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="v1udg8y9h"/><stop offset="1" class="xwe1sccdw"/></radialGradient><radialGradient id="ieMT60d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65365 0 0 -1.07747 10.491 15.499)" gradientUnits="userSpaceOnUse"><stop class="i6ke_7bgx"/><stop offset="1" class="o4zo9ruqr"/></radialGradient><radialGradient id="i0vIgNe" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 .04287 -.03776 .84633 21.369 15.448)" gradientUnits="userSpaceOnUse"><stop class="e-ep_k--r"/><stop offset=".809" class="a7xqbjbil"/></radialGradient><radialGradient id="ib71Hqe" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 -1.091 15.5)scale(7.05349 6.17563)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="ov0uq3bqi"/><stop offset="1" class="sc5jrsb0b"/></radialGradient><radialGradient id="in5utCd" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.957 8.251)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="ianvqSH" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.98 14.584)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iOAhnad" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.167 6.772)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="i50HDKe" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.574 5.633)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="ifC2ncc" cx="0" cy="0" r="1" gradientTransform="rotate(158.664 4.7 10.01)scale(5.43502 6.37816)" gradientUnits="userSpaceOnUse"><stop class="vi2d-bqgl"/><stop offset="1" class="e0s8bocva"/></radialGradient><radialGradient id="iJj6fAb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.543 6.146)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iT1p4BP" cx="0" cy="0" r="1" gradientTransform="matrix(5.0625 -2.5 8.03057 16.26191 2.533 21.976)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="aeh-ojcyt"/><stop offset="1" class="eg11r1-xe"/></radialGradient><radialGradient id="izkTnEb" cx="0" cy="0" r="1" gradientTransform="matrix(5.3125 1.875 -1.76947 5.01351 20.72 14.6)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="mfg03v23s"/><stop offset="1" class="dthyi0lfx"/></radialGradient><radialGradient id="iVfic0d" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1.5 3.12608 5.73115 20.845 10.35)" gradientUnits="userSpaceOnUse"><stop class="r0jlw3bfn"/><stop offset="1" class="fupaa8bps"/></radialGradient><radialGradient id="im8Z1uc" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 1.625 -3.0178 6.26772 20.783 16.976)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="qqqjyabvn"/><stop offset="1" class="soqvob0bo"/></radialGradient><radialGradient id="icHg3Rj" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.058 6.272)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ictyttc" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.117 5.629)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="i4olntC" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.088 6.272)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ipIrvKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.031 4.959)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="iu6jDXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.225 5.166)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="iQaNNAd" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.23 5.866)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="xrgskrbeu"/><stop offset="1" class="youzx1gsf"/></radialGradient><radialGradient id="iIcKf0d" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.578 3.413)" gradientUnits="userSpaceOnUse"><stop class="i0xt980of"/><stop offset="1" class="n1psrewes"/></radialGradient><radialGradient id="idOfR2I" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.454 5.257)" gradientUnits="userSpaceOnUse"><stop class="vkm05yehh"/><stop offset=".759" class="mzksnyx6l"/></radialGradient><radialGradient id="it5JL3d" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.105 1.85)" gradientUnits="userSpaceOnUse"><stop class="uph7y6b-c"/><stop offset="1" class="ufznmm6ku"/></radialGradient><radialGradient id="itGO1it" cx="0" cy="0" r="1" gradientTransform="matrix(-7.91736 5.03207 -2.78747 -4.38576 22.48 26.319)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="r6lo6r6nk"/><stop offset="1" class="y46jxob_z"/></radialGradient><radialGradient id="iHSnOIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.15093 -1.2516 6.27758 -.757 12.899 3.223)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="imegOtd" cx="0" cy="0" r="1" gradientTransform="rotate(55.635 5.041 11.99)scale(4.22355 4.62851)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="dx7h84bsl"/><stop offset=".896" class="e7f2o7b6i"/></radialGradient><radialGradient id="iLoVxkd" cx="0" cy="0" r="1" gradientTransform="matrix(.16688 -1.62542 5.33705 .54795 19.599 3.398)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="iapKp5d" cx="0" cy="0" r="1" gradientTransform="rotate(-91.151 8.86 -5.069)scale(1.21254 6.13593)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iJeulZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.63304 2.73066 -3.00756 1.79864 13.648 1.856)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="iwgROoe" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 -2.125 7.91564 .34922 18.61 4.32)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="iaI6Bab" cx="0" cy="0" r="1" gradientTransform="matrix(.04203 -1.1037 3.99518 .15214 13.94 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="isyjyZj" cx="0" cy="0" r="1" gradientTransform="rotate(57.127 3.89 14.008)scale(2.59234 3.1316)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="i7yjFid" cx="0" cy="0" r="1" gradientTransform="matrix(.01562 -1.15625 4.63352 .06261 18.469 4.522)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="iPt7U6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.05908 -1.21917 3.8426 -.1862 13.51 5.64)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="igtd1lb" cx="0" cy="0" r="1" gradientTransform="rotate(85.073 5.271 8.859)scale(3.92006 3.10284)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="ik3Vzxb" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.766 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="igteJrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.845 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="s_7ldyban"/><stop offset="1" class="wuo647bgi"/></radialGradient><radialGradient id="iIQDn4c" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 8.998 -1.336)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="gt3x42bpl"/><stop offset="1" class="grtoohbub"/></radialGradient><radialGradient id="iPBFoce" cx="0" cy="0" r="1" gradientTransform="rotate(-36.852 14.11 -9.57)scale(3.60415 1.2911)" gradientUnits="userSpaceOnUse"><stop class="antc_rrkm"/><stop offset="1" class="jqq63xj1b"/></radialGradient><linearGradient id="iue2uzK" x1="21.558" x2="19.906" y1="16.601" y2="16.538" gradientUnits="userSpaceOnUse"><stop class="epcmylbkj"/><stop offset="1" class="rnpfigb9v"/></linearGradient><linearGradient id="iSvsX2d" x1="17.049" x2="15.943" y1="16.194" y2="16.301" gradientUnits="userSpaceOnUse"><stop class="pgf79f9wa"/><stop offset="1" class="y5mdemb8a"/></linearGradient><linearGradient id="iq2eBtz" x1="16.095" x2="16.095" y1="17.772" y2="16.988" gradientUnits="userSpaceOnUse"><stop offset=".039" class="w7rs9ac1v"/><stop offset="1" class="w39olobsu"/></linearGradient><linearGradient id="iOo0yQe" x1="15.943" x2="15.943" y1="14.615" y2="15.234" gradientUnits="userSpaceOnUse"><stop offset=".063" class="jlulfbbrt"/><stop offset="1" class="g65e9lolk"/></linearGradient><linearGradient id="iXsW89c" x1="16.605" x2="16.605" y1="5.566" y2="13.803" gradientUnits="userSpaceOnUse"><stop class="rxy3d1mqt"/><stop offset=".622" class="ovy025hqy"/></linearGradient><linearGradient id="ivuPxEJ" x1="19.166" x2="18.824" y1="14.94" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqDZooO" x1="14.377" x2="14.036" y1="14.94" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imeLlBe" x1="13.719" x2="11.576" y1="12.32" y2="13.064" gradientUnits="userSpaceOnUse"><stop class="gh9gt_b2a"/><stop offset="1" class="ztcw_xbmr"/></linearGradient><linearGradient id="ify8Wza" x1="19.478" x2="17.096" y1="12.538" y2="12.214" gradientUnits="userSpaceOnUse"><stop class="gh9gt_b2a"/><stop offset="1" class="ztcw_xbmr"/></linearGradient><linearGradient id="iJIb9je" x1="14.97" x2="15.458" y1="19.495" y2="18.613" gradientUnits="userSpaceOnUse"><stop class="gpnvx3bhh"/><stop offset=".537" class="d2t_iz3lq"/></linearGradient><linearGradient id="iiyPxme" x1="24.522" x2="10.056" y1="12.742" y2="32.591" gradientUnits="userSpaceOnUse"><stop class="c8jr--_9q"/><stop offset=".9" class="zxn8nz0ch"/></linearGradient><linearGradient id="i6X8AKd" x1="11.261" x2="7.292" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="d23tlbbur"/><stop offset=".582" class="eoe3ifbfq"/></linearGradient><linearGradient id="iga8YZd" x1="14.256" x2="10.73" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".565" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iiFiDbc" x1="16.571" x2="20.713" y1="2.557" y2="4.814" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".704" class="aphqukgtk"/></linearGradient><linearGradient id="im6WHLd" x1="15.281" x2="12.229" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iPB1SIb" x1="15.539" x2="20.268" y1="3.462" y2="4.851" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="i4Sz9jc" x1="14.951" x2="12.46" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iUAWlct" x1="16.259" x2="19.168" y1="4.234" y2="5.677" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="ivhKXJc" x1="14.466" x2="11.783" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iv8VgJe" x1="16.795" x2="20.014" y1="5.254" y2="6.073" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="ijecnMc" x1="14.645" x2="11.594" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="ir4u4PN" x1="15.116" x2="11.594" y1="4.207" y2="5.388" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="iG8IWhG" x1="15.249" x2="11.729" y1="3.221" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="i3fCmqc" x1="14.43" x2="11.184" y1="2.409" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><filter id="iM9oXbd" width="11.877" height="14.137" x="10.431" y="8.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.470588 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3728" result="effect2_innerShadow_4002_3728"/></filter><filter id="i3rNQad" width="4.044" height="5.157" x="13.696" y="13.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".5"/></filter><filter id="inW0V3b" width="2.244" height="3.357" x="14.821" y="14.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".05"/></filter><filter id="iFWrwWd" width="14.015" height="9.054" x="8.935" y="5.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0196078 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/></filter><filter id="iRK2Gte" width="7.25" height="6.272" x="9.295" y="6.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341667 0 0 0 0 0.324583 0 0 0 0 0.324583 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/><feGaussianBlur result="effect2_foregroundBlur_4002_3728" stdDeviation=".15"/></filter><filter id="ixbjzMc" width="6.98" height="5.963" x="15.919" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/><feGaussianBlur result="effect2_foregroundBlur_4002_3728" stdDeviation=".15"/></filter><filter id="ix8rxUc" width=".839" height=".74" x="17.528" y="14.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".05"/></filter><filter id="im31bwc" width=".935" height=".959" x="18.452" y="14.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".1"/></filter><filter id="iX2FFmd" width="1.038" height="1.097" x="13.615" y="14.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".1"/></filter><filter id="ibDUHEN" width=".976" height=".749" x="12.784" y="14.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".05"/></filter><filter id="iE1fIqe" width="1.402" height="2.546" x="9.397" y="14.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="i46ikwj" width="1.531" height="2.572" x="21.158" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="i5H1gFd" width="2.544" height="1.086" x="11.838" y="11.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.0705882 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/></filter><filter id="iCWh7lc" width="2.594" height="1.136" x="11.763" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="iGb8Vae" width="2.544" height="1.086" x="17.604" y="11.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.0705882 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3728"/></filter><filter id="igq1Bwe" width="2.594" height="1.136" x="17.529" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="iy2QBnn" width="16.188" height="8.656" x="9.167" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".5"/></filter><filter id="iCLqomc" width="4.094" height="4.656" x="7.917" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".25"/></filter><filter id="ixrIoeb" width="3.508" height="1.177" x="11.47" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="iH43H2b" width="4.104" height="1.115" x="11.336" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="iwMZRse" width="4.104" height="1.115" x="11.47" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter><filter id="i8fPqcd" width="4.288" height="1.471" x="10.456" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3728" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok-light" /></template>
<style>
.a-yl-3btr {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.446 18.332c.44.23.965.36 1.524.36a3.3 3.3 0 0 0 1.524-.36a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.262m-3.334-.305l3.292.277m-3.292-.277a.22.22 0 0 0-.263.045a.2.2 0 0 0-.022.26m.285-.305l-.244.277m3.578.028l-.042-.027m.042.027l-.042-.027m.042.027c-.383.58-1.05.967-1.81.967s-1.426-.386-1.81-.966m3.578-.029a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.944m-.041.027v.001l.04-.029m-.04.028l.04-.027");
}

.a7xqbjbil {
  stop-color: var(--svg-color--c37f6f, #C37F6F);
}

.a9n1f6bpa {
  stop-color: var(--svg-color--f7b9a7, #F7B9A7);
  stop-opacity: 0;
}

.aeh-ojcyt {
  stop-color: var(--svg-color--c7482a, #C7482A);
}

.afwn1lnfh {
  d: path("M14.453 15.22c0-.314-.255-.524-.324-.587l-.314.304l.193.393z");
}

.agt7cdzvy {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
  stop-opacity: 0;
}

.antc_rrkm {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
}

.aphqukgtk {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
  stop-opacity: 0;
}

.aqwz8eb5i {
  stop-color: var(--svg-color--494748, #494748);
  stop-opacity: 0;
}

.au361rb0r {
  stop-color: var(--svg-color--5f443e, #5F443E);
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.bf8qmd23r {
  d: path("M23.933 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.bl2yw2f5t {
  stop-color: var(--svg-color--bf876a, #BF876A);
  stop-opacity: 0;
}

.bo9ofmw9k {
  stop-color: var(--svg-color--251421, #251421);
}

.bxh6ncchi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.773 12.757c-.266-.194-1.017-.545-1.894-.404");
}

.by6guy4wy {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
  stop-opacity: 0;
}

.bykdelbyf {
  stop-color: var(--svg-color--b46653, #B46653);
  stop-opacity: 0;
}

.c8jr--_9q {
  stop-color: var(--svg-color--ff610f, #FF610F);
}

.cb1ljub6x {
  d: path("M9.51 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.005 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.219.696-.414c.063-.133.064-.316-.03-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .057-.625c.156-.062.336-.304.312-.648c-.037-.538-.494-.371-.713-.366l-.232-.29c.012-.55-.585-.6-.815-.575l-1.717.098a.98.98 0 0 0-.765-.133c-.432.123-1.264.339-2.094 1.047");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d23tlbbur {
  stop-color: var(--svg-color--ff6d39, #FF6D39);
}

.d2t_iz3lq {
  stop-color: var(--svg-color--e1aba4, #E1ABA4);
  stop-opacity: 0;
}

.d879qkbvi {
  d: path("M18.25 14.568c.069.092-.076.205-.24.328c-.165.123-.287.21-.356.117c-.07-.092.008-.267.172-.39c.165-.123.354-.148.424-.055");
}

.d8ptwz9tw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.615 3.49c.43-.109 1.65-.273 2.666-.148");
}

.dain57iqy {
  fill: var(--svg-color--000, #000);
  d: path("M17.765 15.334c0-.31.247-.557.556-.557a.554.554 0 0 1 .495.813h-.985a.5.5 0 0 1-.066-.256");
}

.dbid5acei {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.12 3.627c-.43-.11-2.375-.477-3.254-.266");
}

.dc7v1rsdf {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
  stop-opacity: 0;
}

.dg217h9if {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.113 12.757c.266-.194 1.017-.545 1.894-.404");
}

.dges7ib9m {
  d: path("m7.392 4.635l-.428.666a.24.24 0 0 0 .01.278c.898 1.155 2.373 1.801 3.283 2.087a.244.244 0 0 0 .28-.107c.151-.248.354-.585.41-.69c.068-.131-.03-.232-.086-.265L7.845 4.775l.125-.273c-.35-.106-.531.044-.578.133");
}

.di5jaebmp {
  fill: var(--svg-color--e3a59a, #E3A59A);
  d: path("m15.414 15.16l-.691 2.002c-.119.412.165.823.566.823h.857c.401 0 .684-.418.566-.823l-.578-2.001c-.124-.444-.59-.444-.72 0");
}

.do-g6qb_k {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
}

.dqa_-7bzp {
  d: path("M16.222 9.305a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.647-3.823 3.68v.299c-.37-.282-.676-.57-.676-1.53c0-1.61 2.705-3.59 4.105-3.96a6 6 0 0 1 1.723-.178c.468.017.8.42.805.888l.016 1.391z");
}

.dthyi0lfx {
  stop-color: var(--svg-color--df5212, #DF5212);
  stop-opacity: 0;
}

.dx7h84bsl {
  stop-color: var(--svg-color--d09b80, #D09B80);
  stop-opacity: 0;
}

.e-ep_k--r {
  stop-color: var(--svg-color--c47f6e, #C47F6E);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0s8bocva {
  stop-color: var(--svg-color--d64d38, #D64D38);
  stop-opacity: 0;
}

.e7f2o7b6i {
  stop-color: var(--svg-color--d09b80, #D09B80);
}

.eg11r1-xe {
  stop-color: var(--svg-color--c7482a, #C7482A);
  stop-opacity: 0;
}

.elwg_hb8v {
  stop-color: var(--svg-color--383636, #383636);
}

.eoe3ifbfq {
  stop-color: var(--svg-color--ff6d39, #FF6D39);
  stop-opacity: 0;
}

.epcmylbkj {
  stop-color: var(--svg-color--de9b86, #DE9B86);
}

.eusvtmb2r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.667 26.678c.48-.448 1.67-1.706 2.594-3.156");
}

.ew05122nr {
  stop-color: var(--svg-color--3f383b, #3F383B);
  stop-opacity: 0;
}

.ew56wjbup {
  stop-color: var(--svg-color--ff7532, #FF7532);
}

.ezh02gbvd {
  stop-color: var(--svg-color--323030, #323030);
}

.ezip59b9l {
  stop-color: var(--svg-color--c78389, #C78389);
}

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.f0qoe92_d {
  cx: 13.272px;
  cy: 14.777px;
  rx: 0.424px;
  ry: 0.215px;
}

.f4ksqbb1r {
  stop-color: var(--svg-color--d6978c, #D6978C);
}

.fawmdr3-g {
  stop-color: var(--svg-color--d29d82, #D29D82);
}

.fbkqlsb6l {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M21.784 12.96v-.665c-.012-.831-.896-1.514-1.727-1.549h-1.525c-1.237 0-1.936-.897-2.273-1.948c-.236-.735.626-1.31 1.388-1.185c.889.146 1.886.248 3.349 1.112c2.215 1.308 1.788 3.183.788 4.235");
}

.fjyqc_bny {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.852 5.381c-.274-.102-1.102-.305-2.172-.242");
}

.fk9nbx4th {
  d: path("M21.229 8.493a2.53 2.53 0 0 1 1.38 1.145a2.58 2.58 0 0 1-.116 2.75a1.7 1.7 0 0 0-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.75a1.58 1.58 0 0 0-1.502-1.559h-1.524c-1.04 0-1.98-.613-2.408-1.57a.72.72 0 0 0-.67-.456h-1.386c-2.01 0-3.638 1.647-3.638 3.68l.034 1.673c-.277.04-.566.133-.784.287V13.34c0-.339-.104-.671-.295-.952a2.6 2.6 0 0 1-.156-2.663A2.55 2.55 0 0 1 10.644 8.5c.624-.222 1.026-.607 1.378-1.174c.45-.718 1.37-1.232 2.277-1.232c.353 0 .687.046.999.174c.416.181.883.181 1.299 0c.306-.128.641-.174.994-.174c.918 0 1.72.497 2.165 1.232c.335.555.86.958 1.473 1.168");
}

.fohmhtbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 5.561c.391-.173 1.476-.503 2.758-.41");
}

.fsxm9dwni {
  d: path("M10.69 18.736a4.26 4.26 0 0 0 4.23 3.708h2.055a4.26 4.26 0 0 0 4.23-3.708c.129-2.051.258-4.094.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.613-2.408-1.57a.72.72 0 0 0-.67-.456H14.07c-2.01 0-3.638 1.647-3.638 3.68c0 2.025.126 4.018.26 6.049");
}

.ft5dv1b6b {
  fill: none;
}

.fupaa8bps {
  stop-color: var(--svg-color--da531c, #DA531C);
  stop-opacity: 0;
}

.fv_h9xbci {
  d: path("M21.408 16.484q.063-1.035.12-2.072a1.04 1.04 0 0 1-.12 2.072");
}

.g65e9lolk {
  stop-color: var(--svg-color--f2c1ac, #F2C1AC);
  stop-opacity: 0;
}

.gavknk-rw {
  stop-color: var(--svg-color--25171d, #25171D);
}

.gfer3rbfb {
  d: path("M19.186 15.206a.9.9 0 0 0-.252-.504l-.282.31l.127.25z");
}

.gg4pweb1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.492 4.303c-.43-.11-1.28-.203-2.296-.078");
}

.gh9gt_b2a {
  stop-color: var(--svg-color--2d2c2c, #2D2C2C);
}

.gpnvx3bhh {
  stop-color: var(--svg-color--e1aba4, #E1ABA4);
}

.grtoohbub {
  stop-color: var(--svg-color--ce9488, #CE9488);
  stop-opacity: 0;
}

.gt3x42bpl {
  stop-color: var(--svg-color--ce9488, #CE9488);
}

.gyc1lm0xs {
  width: 4.615px;
  height: 6.587px;
  x: 13.663px;
  y: 17.985px;
  rx: 2.307px;
}

.h-jczlzen {
  d: path("M21.236 17.086c.365-.011.706-.135.985-.336v1.014c0 .972-.58 1.839-1.46 2.198q.28-.594.376-1.285z");
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.h9nb3dbmm {
  d: path("m15.527 14.948l-.579 2.001c-.118.412.165.823.567.823h.856c.402 0 .685-.418.567-.823l-.579-2.002c-.124-.443-.702-.443-.832 0");
}

.hi0vjzatb {
  d: path("M18.321 14.362a.972.972 0 0 1 .936 1.228H17.38a.975.975 0 0 1 .94-1.228");
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.hwvoaqesi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.34 14.066a1.52 1.52 0 0 0-1.475 1.153a.3.3 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.525 1.525 0 0 0-1.493-1.228");
}

.i-377o6ky {
  d: path("M7.307 5.365c-.203-.057-.677-.154-.945-.086c-.336.086-.594.329-.813.688c-.175.287-1.469 2.48-2.094 3.539c-.562.823-1.625 3.088-1.375 5.563c.1 1.662.782 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.157.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.375-5.563a915 915 0 0 0-2.094-3.54c-.219-.358-.477-.6-.813-.687c-.268-.068-.742.03-.945.086L21.494 7.53c-.351.415-.19.967-.054 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.484a4.3 4.3 0 0 1-.775.336v.024a2.307 2.307 0 1 1-4.614 0v-.01a4.3 4.3 0 0 1-.782-.328c-.395.155-.762.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.136-.213.297-.765-.055-1.18z");
}

.i0xt980of {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
}

.i6ke_7bgx {
  stop-color: var(--svg-color--cb7561, #CB7561);
}

.icf7hpmps {
  stop-color: var(--svg-color--ffcfbc, #FFCFBC);
}

.igo7pk_ym {
  d: path("M9.51 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.005 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.219.696-.414c.063-.133.064-.316-.03-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .057-.625c.156-.062.336-.304.312-.648c-.037-.538-.562-.662-.781-.656H14.9c.012-.55-.585-.6-.815-.575l-1.717.098a.98.98 0 0 0-.765-.133c-.432.123-1.264.339-2.094 1.047");
}

.ipg0cn99k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.295 5.381c.273-.102 1.101-.305 2.171-.242");
}

.iziaq4wdz {
  stop-color: var(--svg-color--d29d82, #D29D82);
  stop-opacity: 0;
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jlulfbbrt {
  stop-color: var(--svg-color--f2c1ac, #F2C1AC);
}

.jqq63xj1b {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
  stop-opacity: 0;
}

.jt8x2h0ur {
  stop-color: var(--svg-color--d6978c, #D6978C);
  stop-opacity: 0;
}

.jx3zfg-wy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.654 4.303c.43-.11 1.281-.203 2.297-.078");
}

.kg5wfpbcx {
  stop-color: var(--svg-color--413735, #413735);
}

.khto69bzj {
  stop-color: var(--svg-color--130402, #130402);
}

.lfjjhubys {
  stop-color: var(--svg-color--413735, #413735);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lsgwilbat {
  stop-color: var(--svg-color--c78389, #C78389);
  stop-opacity: 0;
}

.lulnx3bbe {
  cx: 13.272px;
  cy: 14.777px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.424px;
  ry: 0.215px;
}

.mfg03v23s {
  stop-color: var(--svg-color--df5212, #DF5212);
}

.mlgnx_bnj {
  stop-color: var(--svg-color--b9816d, #B9816D);
  stop-opacity: 0;
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.mxpallb1y {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.25 14.568c.069.092-.076.205-.24.328c-.165.123-.287.21-.356.117c-.07-.092.008-.267.172-.39c.165-.123.354-.148.424-.055");
}

.mzksnyx6l {
  stop-color: var(--svg-color--f4c7ad, #F4C7AD);
}

.n1psrewes {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
  stop-opacity: 0;
}

.n2xzttb7n {
  fill: var(--svg-color--211419, #211419);
  d: path("M16.222 9.305a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.647-3.823 3.68v.299c-.37-.282-.676-.57-.676-1.53c0-1.61 2.705-3.59 4.105-3.96a6 6 0 0 1 1.723-.178c.468.017.8.42.805.888l.016 1.391z");
}

.nax04kucn {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.07 3.186c-.68-.344-2.469-.57-3.188-.524");
}

.nh2kw4_uc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.07 3.186c-.68-.344-2.469-.57-3.188-.524");
}

.nh7q47k8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.711 4.465c.46-.173 1.847-.438 3.354-.346");
}

.nq6rqyi_k {
  fill: var(--svg-color--0f0e0d, #0F0E0D);
  fill-rule: evenodd;
  d: path("M17.922 12.624c.79-.126 1.468.194 1.69.355a.275.275 0 1 0 .323-.445c-.31-.226-1.134-.608-2.1-.453a.275.275 0 0 0 .087.543");
}

.nrnvctv1v {
  d: path("M10.45 13.714a1.75 1.75 0 0 0-1.515 1.723c0 .935.733 1.699 1.656 1.749a84 84 0 0 1-.14-3.472");
}

.nu0bve_mm {
  stop-color: var(--svg-color--e9b5a3, #E9B5A3);
}

.o4zo9ruqr {
  stop-color: var(--svg-color--ce7a67, #CE7A67);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oju6c_bmm {
  stop-color: var(--svg-color--4d4749, #4D4749);
}

.okxecjbze {
  stop-color: var(--svg-color--433a37, #433A37);
}

.ov0uq3bqi {
  stop-color: var(--svg-color--cc472d, #CC472D);
}

.ovy025hqy {
  stop-color: var(--svg-color--2e2a30, #2E2A30);
}

.p0trpqw-l {
  stop-color: var(--svg-color--b46c5f, #B46C5F);
}

.pgf79f9wa {
  stop-color: var(--svg-color--ffd2be, #FFD2BE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppk0kktky {
  d: path("M21.302 17.185q.108-1.736.2-3.474a1.753 1.753 0 0 1-.2 3.474");
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.q3305mbzy {
  stop-color: var(--svg-color--f4c0ae, #F4C0AE);
}

.qd38sjb7e {
  stop-color: var(--svg-color--ff7532, #FF7532);
  stop-opacity: 0;
}

.ql2vfvfmz {
  stop-color: var(--svg-color--f7b9a7, #F7B9A7);
}

.qqqjyabvn {
  stop-color: var(--svg-color--da4f1a, #DA4F1A);
}

.qsgc35tqu {
  stop-color: var(--svg-color--b9816d, #B9816D);
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.qy05b9bsw {
  stop-color: var(--svg-color--494748, #494748);
}

.r0jlw3bfn {
  stop-color: var(--svg-color--da531c, #DA531C);
}

.r6lo6r6nk {
  stop-color: var(--svg-color--ff8748, #FF8748);
}

.rnpfigb9v {
  stop-color: var(--svg-color--de9b86, #DE9B86);
  stop-opacity: 0;
}

.rotm0lbjl {
  stop-color: var(--svg-color--3a3233, #3A3233);
}

.rrphcb4zv {
  d: path("M22.637 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .027.054c.032.573-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.219-.695-.414c-.064-.133-.065-.316.029-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.056-.625c-.157-.062-.337-.304-.313-.648c.038-.538.592-.465.81-.46l.136-.196c-.013-.55.585-.6.814-.575l1.717.098a.98.98 0 0 1 .766-.133c.432.123 1.263.339 2.093 1.047");
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.rxy3d1mqt {
  stop-color: var(--svg-color--383435, #383435);
}

.s_7ldyban {
  stop-color: var(--svg-color--cd978c, #CD978C);
  stop-opacity: 0;
}

.s59e5ab9a {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
}

.sc5jrsb0b {
  stop-color: var(--svg-color--cc472d, #CC472D);
  stop-opacity: 0;
}

.sdjfhcbou {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.12 3.627c-.43-.11-2.375-.477-3.254-.266");
}

.soqvob0bo {
  stop-color: var(--svg-color--da4f1a, #DA4F1A);
  stop-opacity: 0;
}

.sx2208btj {
  d: path("M21.784 12.96v-.665c-.012-.831-.896-1.514-1.727-1.549h-1.525c-1.237 0-1.936-.897-2.273-1.948c-.236-.735.626-1.31 1.388-1.185c.889.146 1.886.248 3.349 1.112c2.215 1.308 1.788 3.183.788 4.235");
}

.t399fcb5k {
  stop-color: var(--svg-color--cb736b, #CB736B);
}

.t39rzsbyn {
  stop-color: var(--svg-color--4d4749, #4D4749);
  stop-opacity: 0;
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.tpx6wbcio {
  stop-color: var(--svg-color--251421, #251421);
  stop-opacity: 0;
}

.u-qvctb2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.852 5.381c-.274-.102-1.102-.305-2.172-.242");
}

.uaxsyh7oh {
  fill: var(--svg-color--000, #000);
  d: path("M14.122 15.334a.554.554 0 0 0-.557-.557a.554.554 0 0 0-.494.813h.985a.55.55 0 0 0 .066-.256");
}

.ufznmm6ku {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
  stop-opacity: 0;
}

.uj-nym00r {
  stop-color: var(--svg-color--f4c0ae, #F4C0AE);
  stop-opacity: 0;
}

.uph7y6b-c {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
}

.uz3hg9bsf {
  d: path("M22.637 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .027.054c.032.573-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.219-.695-.414c-.064-.133-.065-.316.029-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.056-.625c-.157-.062-.337-.304-.313-.648c.038-.538.563-.662.782-.656h.164c-.013-.55.585-.6.814-.575l1.717.098a.98.98 0 0 1 .766-.133c.432.123 1.263.339 2.093 1.047");
}

.v1udg8y9h {
  stop-color: var(--svg-color--d27f6f, #D27F6F);
}

.v61f_wbit {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.077 3.186c.68-.344 2.468-.57 3.187-.524");
}

.vaqwmfbyh {
  stop-color: var(--svg-color--b46653, #B46653);
}

.vi2d-bqgl {
  stop-color: var(--svg-color--d64d38, #D64D38);
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vkm05yehh {
  stop-color: var(--svg-color--ffdabd, #FFDABD);
}

.vtekkxd_w {
  d: path("m24.755 4.635l.428.666a.24.24 0 0 1-.01.278c-.9 1.155-2.374 1.801-3.283 2.087a.244.244 0 0 1-.281-.107a22 22 0 0 1-.409-.69c-.069-.131.029-.232.086-.265L24.3 4.775l-.124-.273c.35-.106.53.044.578.133");
}

.vtzl6jmuj {
  fill: var(--svg-color--0f0e0d, #0F0E0D);
  fill-rule: evenodd;
  d: path("M13.964 12.624c-.79-.126-1.468.194-1.69.355a.275.275 0 1 1-.323-.445c.31-.226 1.134-.608 2.1-.453a.275.275 0 1 1-.087.543");
}

.vxljdps-k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 3.48c.46-.173 1.847-.439 3.353-.347");
}

.vxpddkamp {
  stop-color: var(--svg-color--ffc2af, #FFC2AF);
}

.vzv6bacbx {
  stop-color: var(--svg-color--bf876a, #BF876A);
}

.w39olobsu {
  stop-color: var(--svg-color--e5a99e, #E5A99E);
  stop-opacity: 0;
}

.w7rs9ac1v {
  stop-color: var(--svg-color--e5a99e, #E5A99E);
}

.wgttxsdys {
  stop-color: var(--svg-color--3a3233, #3A3233);
  stop-opacity: 0;
}

.wgy-qlbik {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.83 3.08c.434-.236 2.033-.622 3.539-.722");
}

.wiieli2ej {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.546 14.066c.711 0 1.312.49 1.475 1.153a.298.298 0 0 1-.291.371H17.3a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.228");
}

.wu2h8jb4k {
  d: path("M13.565 14.362a.972.972 0 0 0-.936 1.228h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.972");
}

.wuo647bgi {
  stop-color: var(--svg-color--a97265, #A97265);
}

.wx87iwb8j {
  stop-color: var(--svg-color--3f383b, #3F383B);
}

.x-kyklb-a {
  stop-color: var(--svg-color--383636, #383636);
  stop-opacity: 0;
}

.xl-zenb2y {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
}

.xrgskrbeu {
  stop-color: var(--svg-color--fcc4ac, #FCC4AC);
}

.xuzndv0cv {
  fill: var(--svg-color--f7c1ab, #F7C1AB);
  d: path("m15.527 14.948l-.579 2.001c-.118.412.165.823.567.823h.856c.402 0 .685-.418.567-.823l-.579-2.002c-.124-.443-.702-.443-.832 0");
}

.xwe1sccdw {
  stop-color: var(--svg-color--e09982, #E09982);
}

.y2a69ng6x {
  stop-color: var(--svg-color--ffcfbc, #FFCFBC);
  stop-opacity: 0;
}

.y46jxob_z {
  stop-color: var(--svg-color--ff8748, #FF8748);
  stop-opacity: 0;
}

.y5mdemb8a {
  stop-color: var(--svg-color--ffd2be, #FFD2BE);
  stop-opacity: 0;
}

.y895atbwd {
  stop-color: var(--svg-color--c58274, #C58274);
}

.ygjg_lb-n {
  d: path("M10.459 14.422a1.04 1.04 0 0 0 .09 2.046a85 85 0 0 1-.09-2.046");
}

.ym0brebyc {
  stop-color: var(--svg-color--ff6a31, #FF6A31);
}

.youzx1gsf {
  stop-color: var(--svg-color--edc1a6, #EDC1A6);
}

.ywm5k41wv {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.492 4.303c-.43-.11-1.28-.203-2.296-.078");
}

.ze-agacxi {
  d: path("M10.65 17.086a1.8 1.8 0 0 1-.984-.336v1.014c0 .972.579 1.839 1.46 2.198a4.5 4.5 0 0 1-.377-1.285z");
}

.ze5ugdbxr {
  stop-color: var(--svg-color--ff7840, #FF7840);
}

.ztcw_xbmr {
  stop-color: var(--svg-color--2d2c2c, #2D2C2C);
  stop-opacity: 0;
}

.zxn8nz0ch {
  stop-color: var(--svg-color--fb5b1a, #FB5B1A);
}

</style>
