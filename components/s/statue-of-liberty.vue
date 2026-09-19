<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itEX7ab)" class="lyt0vgkwo"/><path fill="url(#iLGwitb)" class="lyt0vgkwo"/><path fill="url(#iSjVHrb)" class="c4icz31jr"/><path fill="url(#imdZ3Fe)" class="c4icz31jr"/><path fill="url(#i96rVbb)" class="c4icz31jr"/><path fill="url(#iiLu3xd)" class="c4icz31jr"/><path fill="url(#icZGEab)" class="a8o33yldj"/><path fill="url(#iHIpyKd)" class="a8o33yldj"/><path fill="url(#ioyYA2b)" class="a8o33yldj"/><path fill="url(#imuK8XK)" class="a8o33yldj"/><path fill="url(#igWqvse)" class="a8o33yldj"/><path fill="url(#iY3KA2c)" class="a8o33yldj"/><path fill="url(#iFZjJ8b)" class="a8o33yldj"/><g filter="url(#iE2ySnb)"><path class="zqsidabqj"/><path fill="url(#ig0IPmb)" class="k8kvjw4cv"/><path fill="url(#ivsZwSL)" class="k8kvjw4cv"/></g><path fill="url(#iOMGW4c)" class="okwn0lbuv"/><path fill="url(#iiE9Ulb)" class="okwn0lbuv"/><path fill="url(#i7bmqbd)" class="okwn0lbuv"/><path fill="url(#i6M7Fbb)" class="okwn0lbuv"/><path fill="url(#iAJIFfm)" class="wgyi1ea7k"/><path fill="url(#iZ3l9wM)" class="wgyi1ea7k"/><path fill="url(#ilYcw7d)" class="wgyi1ea7k"/><path fill="url(#iVHKboU)" class="wgyi1ea7k"/><path fill="url(#inTgZCT)" class="hu5k88bjf"/><path fill="url(#iYI9F9d)" class="hu5k88bjf"/><path fill="url(#ihqt87u)" class="hu5k88bjf"/><g filter="url(#izaSGFd)"><path class="mgufbdjop"/><path fill="url(#iaW1EHe)" class="pnw_nc7ij"/></g><path fill="url(#iq11h3b)" class="er04-jy3v"/><path fill="url(#ik5Vvpd)" class="l2s911v2j"/><path fill="url(#iVWHE5c)" class="l2s911v2j"/><path fill="url(#ivBvpAX)" class="l2s911v2j"/><path fill="url(#iCRNmlR)" class="l2s911v2j"/><path fill="url(#ilZAwgd)" class="l2s911v2j"/><path class="e8vsonbis"/><path fill="url(#ioHBLMc)" class="ay0flwb7z"/><path fill="url(#i2QAcEe)" class="ay0flwb7z"/><path class="iv1x16gyo"/><path fill="url(#iVU4vYD)" class="ibj47bx7y"/><g filter="url(#i6lsqkb)"><path fill="url(#i8SWDVc)" class="i5t2gib7w"/><path fill="url(#i8SWDVc)" class="wnyo68gca"/></g><g filter="url(#ias1RQc)"><path fill="url(#i8Y3vXb)" class="pak8nbczp"/></g><path fill="url(#ivWDuSc)" class="pak8nbczp"/><g filter="url(#iGx1AEd)"><path class="rp_b4p_2t"/></g><g filter="url(#iOLsXmc)"><path fill="url(#iVYU84d)" class="ms7pevthj"/><path fill="url(#igczt5c)" class="ms7pevthj"/></g><path fill="url(#i4WHACb)" class="ms7pevthj"/><path fill="url(#iYEVU5J)" class="ms7pevthj"/><path fill="url(#iwe30fb)" class="ms7pevthj"/><path fill="url(#i96G55V)" class="ms7pevthj"/><path fill="url(#iBfkWxc)" class="ms7pevthj"/><g filter="url(#irx9MYb)"><path class="bu89ge-mj"/></g><g filter="url(#iIM4udd)"><path class="rbokqcbmg"/><path fill="url(#i82MMvb)" class="hri9znbxc"/><path fill="url(#i09OcHb)" class="hri9znbxc"/><path fill="url(#iXrFnDc)" class="hri9znbxc"/></g><path fill="url(#izMB3te)" class="mwpl_9fpq"/><path fill="url(#imaMuvd)" class="mtkbwmb7u"/><path fill="url(#iM2bBCe)" class="yh0rbb_bu"/><path fill="url(#iG8bY5d)" class="yh0rbb_bu"/><path fill="url(#isFK2oc)" class="yh0rbb_bu"/><path fill="url(#iWvTMLe)" class="yh0rbb_bu"/><path fill="url(#if442Wc)" class="yh0rbb_bu"/><path fill="url(#i4lzB8b)" class="yh0rbb_bu"/><path fill="url(#iGk4akb)" class="yh0rbb_bu"/><g filter="url(#iojDlld)"><path class="mv5i1emhz"/></g><rect fill="url(#iw5U1MQ)" class="l47-ff88v"/><rect fill="url(#ipPoLOb)" class="l47-ff88v"/><g filter="url(#iqOwWTc)"><path fill="url(#iM9RMOc)" class="w-ln_ibdv"/><path fill="url(#iLMOe9c)" class="w-ln_ibdv"/></g><g filter="url(#i6S5Ckc)"><path class="n0lp0zbgi"/></g><g filter="url(#iGeTYxv)"><path fill="url(#iyoJTkd)" class="mephmkbvo"/><path fill="url(#ihISGIh)" class="mephmkbvo"/></g><path fill="url(#i4rkiPb)" class="cxi-mebpy"/><path fill="url(#iCMgF9Y)" class="cxi-mebpy"/><path fill="url(#iXUqMWc)" class="d055z9lap"/><path fill="url(#iJYXnab)" class="t033lobmd"/><path fill="url(#iShaEYb)" class="t033lobmd"/><g filter="url(#iHR8Jje)"><path fill="url(#i8Vczqe)" clip-rule="evenodd" class="bwbodgcwv"/></g><g filter="url(#i1Ie6Ob)"><path fill="url(#is0ZbMe)" clip-rule="evenodd" class="xz11brxle"/></g><g filter="url(#ihEwM5b)"><path fill="url(#iw4cafQ)" clip-rule="evenodd" class="q5hee9bot"/></g><g filter="url(#ixkZMOE)"><path fill="url(#i193jqQ)" clip-rule="evenodd" class="ehcb3yb9p"/></g><g filter="url(#iwwtDOV)"><path fill="url(#icwcYAc)" clip-rule="evenodd" class="c1on9ebya"/></g><g filter="url(#iQBCijn)"><path fill="url(#iGe4wUn)" clip-rule="evenodd" class="cqgdrbcyc"/></g><g filter="url(#iM0EY6c)"><path fill="url(#ijwhnHe)" clip-rule="evenodd" class="stzz5qrfu"/></g><g filter="url(#iQF4b2p)"><path fill="url(#iZgvUIc)" clip-rule="evenodd" class="bz9b-y5wp"/></g><g filter="url(#iwD2Amd)"><path fill="url(#i5xEFZd)" class="mu-h0qb7f"/></g><defs><linearGradient id="itEX7ab" x1="13.723" x2="11.12" y1="18.26" y2="18.26" gradientUnits="userSpaceOnUse"><stop class="xls2hrnga"/><stop offset="1" class="r88z36bzg"/></linearGradient><linearGradient id="iLGwitb" x1="12.077" x2="12.116" y1="17.366" y2="17.643" gradientUnits="userSpaceOnUse"><stop class="m8i0a5xfk"/><stop offset="1" class="irs5socky"/></linearGradient><linearGradient id="iSjVHrb" x1="11.999" x2="13.171" y1="13.37" y2="16.261" gradientUnits="userSpaceOnUse"><stop class="tfto-7-2d"/><stop offset="1" class="unfkv33te"/></linearGradient><linearGradient id="imdZ3Fe" x1="12.452" x2="12.413" y1="14.339" y2="14.503" gradientUnits="userSpaceOnUse"><stop class="lkth9zbuf"/><stop offset="1" class="wcqw_fbtw"/></linearGradient><linearGradient id="i96rVbb" x1="12.109" x2="12.369" y1="15.761" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="gubo7nbof"/><stop offset="1" class="kymqy9exi"/></linearGradient><linearGradient id="icZGEab" x1="15.546" x2="14.109" y1="11.792" y2="13.167" gradientUnits="userSpaceOnUse"><stop class="j5f103boh"/><stop offset="1" class="p5oxbibrx"/></linearGradient><linearGradient id="ioyYA2b" x1="12.859" x2="13.054" y1="10.425" y2="10.651" gradientUnits="userSpaceOnUse"><stop class="cwc53gb-h"/><stop offset="1" class="tujjnubop"/></linearGradient><linearGradient id="imuK8XK" x1="14.964" x2="14.867" y1="12.003" y2="12.1" gradientUnits="userSpaceOnUse"><stop class="rx_u74boy"/><stop offset="1" class="zt5vehnyl"/></linearGradient><linearGradient id="iY3KA2c" x1="13.515" x2="13.984" y1="12.604" y2="12.339" gradientUnits="userSpaceOnUse"><stop class="g12sjob6v"/><stop offset="1" class="ow70ixnhn"/></linearGradient><linearGradient id="iOMGW4c" x1="22.722" x2="20.336" y1="10.522" y2="13.869" gradientUnits="userSpaceOnUse"><stop class="s_whom05g"/><stop offset="1" class="ps2fn8z6e"/></linearGradient><linearGradient id="i7bmqbd" x1="21.101" x2="21.23" y1="11.889" y2="12.018" gradientUnits="userSpaceOnUse"><stop class="we-9w0bxb"/><stop offset="1" class="ggqsyjbps"/></linearGradient><linearGradient id="iAJIFfm" x1="25.048" x2="23.931" y1="14.202" y2="17.141" gradientUnits="userSpaceOnUse"><stop class="uayrsd9sk"/><stop offset="1" class="u76brdhhn"/></linearGradient><linearGradient id="iZ3l9wM" x1="22.913" x2="22.945" y1="14.557" y2="14.682" gradientUnits="userSpaceOnUse"><stop class="sq_-5wb3n"/><stop offset="1" class="e99yiccgb"/></linearGradient><linearGradient id="ilYcw7d" x1="25.109" x2="24.546" y1="15.589" y2="14.682" gradientUnits="userSpaceOnUse"><stop class="h7riqn0di"/><stop offset="1" class="u7ws-3b1g"/></linearGradient><linearGradient id="inTgZCT" x1="23.476" x2="23.547" y1="18.052" y2="18.831" gradientUnits="userSpaceOnUse"><stop class="d-7ljnbip"/><stop offset=".924" class="q3oq6vz9t"/></linearGradient><linearGradient id="iYI9F9d" x1="23.658" x2="23.613" y1="17.335" y2="17.62" gradientUnits="userSpaceOnUse"><stop offset=".143" class="d2ssc9m9p"/><stop offset="1" class="ya7_06mkz"/></linearGradient><linearGradient id="iq11h3b" x1="14.214" x2="19.93" y1="15.773" y2="15.773" gradientUnits="userSpaceOnUse"><stop class="mxh57b0xo"/><stop offset=".559" class="hdvzz4bgp"/><stop offset=".883" class="kx9cdabxu"/></linearGradient><linearGradient id="iVWHE5c" x1="22.03" x2="21.405" y1="18.261" y2="18.261" gradientUnits="userSpaceOnUse"><stop class="oxedxck2g"/><stop offset="1" class="x0zahfb1g"/></linearGradient><linearGradient id="iCRNmlR" x1="14.024" x2="16.191" y1="17.588" y2="16.742" gradientUnits="userSpaceOnUse"><stop class="jh5c_du-q"/><stop offset="1" class="gz28-xb7v"/></linearGradient><linearGradient id="iVU4vYD" x1="19.923" x2="21.382" y1="23.512" y2="23.261" gradientUnits="userSpaceOnUse"><stop class="s98_46izs"/><stop offset="1" class="kxmmr8ohx"/></linearGradient><linearGradient id="i8SWDVc" x1="15.491" x2="20.69" y1="19.027" y2="19.027" gradientUnits="userSpaceOnUse"><stop offset=".474" class="e3gs-37ee"/><stop offset="1" class="u10gt7bho"/></linearGradient><linearGradient id="i8Y3vXb" x1="17.484" x2="15.109" y1="15.995" y2="17.007" gradientUnits="userSpaceOnUse"><stop class="duyb3tbgu"/><stop offset="1" class="cmv7idbhl"/></linearGradient><linearGradient id="iVYU84d" x1="21.328" x2="8.39" y1="25.636" y2="31.386" gradientUnits="userSpaceOnUse"><stop class="aefbndbvb"/><stop offset=".432" class="j0-txibgh"/><stop offset="1" class="pjvt9itwd"/></linearGradient><linearGradient id="i82MMvb" x1="8.14" x2="10.109" y1="13.042" y2="13.167" gradientUnits="userSpaceOnUse"><stop class="ri62twb1m"/><stop offset="1" class="ie5i73buq"/></linearGradient><linearGradient id="izMB3te" x1="7.855" x2="8.14" y1="8.233" y2="8.233" gradientUnits="userSpaceOnUse"><stop class="ms97-fb2l"/><stop offset="1" class="b69fp-krl"/></linearGradient><linearGradient id="imaMuvd" x1="8.452" x2="8.28" y1="11.253" y2="11.854" gradientUnits="userSpaceOnUse"><stop offset=".085" class="ppmqlzq3c"/><stop offset="1" class="d6on06wfv"/></linearGradient><linearGradient id="iM2bBCe" x1="10.218" x2="8.827" y1="11.682" y2="11.761" gradientUnits="userSpaceOnUse"><stop class="tvtv-xbxs"/><stop offset="1" class="ubwvvpb-g"/></linearGradient><linearGradient id="iG8bY5d" x1="9.312" x2="9.312" y1="15.104" y2="14.62" gradientUnits="userSpaceOnUse"><stop class="n8v8ybbkk"/><stop offset="1" class="ah1qadbud"/></linearGradient><linearGradient id="isFK2oc" x1="10.04" x2="10.023" y1="8.049" y2="8.399" gradientUnits="userSpaceOnUse"><stop class="g50s7ubyg"/><stop offset="1" class="w8_jb8cly"/></linearGradient><linearGradient id="ipPoLOb" x1="9.015" x2="9.023" y1="6.003" y2="6.229" gradientUnits="userSpaceOnUse"><stop class="cp95njb6g"/><stop offset="1" class="e4otybbbc"/></linearGradient><linearGradient id="i8Vczqe" x1="11.956" x2="12.199" y1="28.241" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="o-gvhvbrt"/><stop offset="1" class="akputy45u"/></linearGradient><linearGradient id="is0ZbMe" x1="15.795" x2="16.448" y1="28.48" y2="28.91" gradientUnits="userSpaceOnUse"><stop class="w4rh60b1o"/><stop offset="1" class="uhcz5gz0o"/></linearGradient><linearGradient id="iw4cafQ" x1="17.874" x2="19.222" y1="28.506" y2="28.883" gradientUnits="userSpaceOnUse"><stop offset=".359" class="dhggytx2e"/><stop offset=".607" class="s0lg6u3wb"/></linearGradient><linearGradient id="i193jqQ" x1="19.501" x2="22.101" y1="29.261" y2="29.077" gradientUnits="userSpaceOnUse"><stop offset=".359" class="dhggytx2e"/><stop offset=".607" class="s0lg6u3wb"/></linearGradient><linearGradient id="icwcYAc" x1="22.678" x2="24.313" y1="29.305" y2="28.448" gradientUnits="userSpaceOnUse"><stop class="kiga47jjh"/><stop offset=".407" class="xaqxb-gfg"/><stop offset=".844" class="vqgfefr-x"/></linearGradient><linearGradient id="iGe4wUn" x1="6.45" x2="7.77" y1="21.67" y2="23.832" gradientUnits="userSpaceOnUse"><stop class="f1ln1rb_x"/><stop offset="1" class="ybx6-ycvx"/></linearGradient><linearGradient id="ijwhnHe" x1="6.858" x2="7.861" y1="23.994" y2="25.721" gradientUnits="userSpaceOnUse"><stop class="f1ln1rb_x"/><stop offset="1" class="ybx6-ycvx"/></linearGradient><linearGradient id="iZgvUIc" x1="5.653" x2="9.616" y1="29.515" y2="25.602" gradientUnits="userSpaceOnUse"><stop class="w5kf_ac1m"/><stop offset="1" class="u-lkfhbji"/></linearGradient><linearGradient id="i5xEFZd" x1="14.015" x2="9.484" y1="21.698" y2="25.055" gradientUnits="userSpaceOnUse"><stop class="kk07kc4ea"/><stop offset="1" class="iwax-d_be"/></linearGradient><radialGradient id="iiLu3xd" cx="0" cy="0" r="1" gradientTransform="rotate(99.174 .706 13.716)scale(1.27411 .64637)" gradientUnits="userSpaceOnUse"><stop class="jp7mejbpx"/><stop offset="1" class="p3u5lsz7v"/></radialGradient><radialGradient id="iHIpyKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06368 .51654 -.4846 -.05974 12.004 8.629)" gradientUnits="userSpaceOnUse"><stop class="od-eadcqw"/><stop offset="1" class="g77t_xbev"/></radialGradient><radialGradient id="igWqvse" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 .4375 -.44404 -.01586 13.25 10.253)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="y8y_fh8gh"/><stop offset="1" class="j4nb20b2f"/></radialGradient><radialGradient id="iFZjJ8b" cx="0" cy="0" r="1" gradientTransform="rotate(-115.761 12.049 2.245)scale(.76881 2.21515)" gradientUnits="userSpaceOnUse"><stop class="mo6vmmbnk"/><stop offset="1" class="qkk--j2dj"/></radialGradient><radialGradient id="ig0IPmb" cx="0" cy="0" r="1" gradientTransform="rotate(142.306 7.598 7.562)scale(.43442 .39609)" gradientUnits="userSpaceOnUse"><stop class="od-eadcqw"/><stop offset="1" class="g77t_xbev"/></radialGradient><radialGradient id="ivsZwSL" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -.52344 2.08423 .49773 17.757 13.268)" gradientUnits="userSpaceOnUse"><stop class="e9a9jtbsy"/><stop offset="1" class="c9jyatbxe"/></radialGradient><radialGradient id="iiE9Ulb" cx="0" cy="0" r="1" gradientTransform="matrix(.57813 -.51563 1.09376 1.22634 20.445 13.956)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="bn5095zay"/><stop offset=".746" class="xn9tf1b7s"/></radialGradient><radialGradient id="i6M7Fbb" cx="0" cy="0" r="1" gradientTransform="rotate(122.829 8.766 11.44)scale(.57643 .60884)" gradientUnits="userSpaceOnUse"><stop class="tcx1gh-5s"/><stop offset="1" class="tlp4qirvp"/></radialGradient><radialGradient id="iVHKboU" cx="0" cy="0" r="1" gradientTransform="rotate(134.091 9.757 12.487)scale(.34807 .4181)" gradientUnits="userSpaceOnUse"><stop class="tcx1gh-5s"/><stop offset="1" class="tlp4qirvp"/></radialGradient><radialGradient id="ihqt87u" cx="0" cy="0" r="1" gradientTransform="matrix(-.7024 0 0 -.81569 26.454 18.13)" gradientUnits="userSpaceOnUse"><stop class="mxfqq4b4d"/><stop offset="1" class="yi194xrdy"/></radialGradient><radialGradient id="iaW1EHe" cx="0" cy="0" r="1" gradientTransform="rotate(127.991 3.922 14.977)scale(2.71614 1.30599)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="wx-8cltds"/><stop offset="1" class="k449cwboi"/></radialGradient><radialGradient id="ik5Vvpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59265 4.5 -10.8744 -1.43216 18.577 14.76)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="y16qbs0dv"/><stop offset="1" class="q9z5afz7o"/></radialGradient><radialGradient id="ivBvpAX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07031 2.92859 0 17.985 16.784)" gradientUnits="userSpaceOnUse"><stop offset=".96" class="wnxh4obgu"/><stop offset="1" class="pmbh4ubba"/></radialGradient><radialGradient id="ilZAwgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.23933 .9319 0 20.751 18.297)" gradientUnits="userSpaceOnUse"><stop class="bib5sfhjr"/><stop offset="1" class="rubefdb9l"/></radialGradient><radialGradient id="ioHBLMc" cx="0" cy="0" r="1" gradientTransform="matrix(.96583 4.38665 -1.591 .3503 15.734 19.569)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="mksqcidgm"/><stop offset="1" class="zxv_msbpq"/></radialGradient><radialGradient id="i2QAcEe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.33418 -.20122 .69102 -8.01604 16.177 21.56)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="ag8g1gmqx"/><stop offset="1" class="dls505b1i"/></radialGradient><radialGradient id="ivWDuSc" cx="0" cy="0" r="1" gradientTransform="rotate(139.736 5.956 11.178)scale(1.03406 .27123)" gradientUnits="userSpaceOnUse"><stop class="qk3m-ijws"/><stop offset="1" class="tt2hce02d"/></radialGradient><radialGradient id="igczt5c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 3.34375 -2.29342 -2.12195 8.64 18.667)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="wef7g9ytd"/><stop offset="1" class="guhf91kno"/></radialGradient><radialGradient id="i4WHACb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56251 4.93749 -7.86318 -10.4511 24.078 25.573)" gradientUnits="userSpaceOnUse"><stop class="ps21kcb3d"/><stop offset="1" class="pix3gmy5p"/></radialGradient><radialGradient id="iYEVU5J" cx="0" cy="0" r="1" gradientTransform="rotate(129.289 2.005 14.12)scale(2.22073 5.43595)" gradientUnits="userSpaceOnUse"><stop class="tf-a-kbst"/><stop offset="1" class="ssraa9bhc"/></radialGradient><radialGradient id="iwe30fb" cx="0" cy="0" r="1" gradientTransform="matrix(6.6875 -3.4375 .88859 1.7287 7.171 30.198)" gradientUnits="userSpaceOnUse"><stop class="wtskyg7of"/><stop offset="1" class="py9z2_kep"/></radialGradient><radialGradient id="i96G55V" cx="0" cy="0" r="1" gradientTransform="matrix(5.8125 -2.5 .54627 1.27008 4.046 25.573)" gradientUnits="userSpaceOnUse"><stop class="v4ej81btm"/><stop offset="1" class="r7fgf1bsx"/></radialGradient><radialGradient id="iBfkWxc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 -4.75 .53666 .64258 5.421 29.48)" gradientUnits="userSpaceOnUse"><stop class="l67868ovp"/><stop offset="1" class="jyai5fbtt"/></radialGradient><radialGradient id="i09OcHb" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 3.625 -1.04132 .09875 8.624 12.182)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="w7zg6sbbt"/><stop offset="1" class="gnqrzsbbr"/></radialGradient><radialGradient id="iXrFnDc" cx="0" cy="0" r="1" gradientTransform="matrix(5.31247 6.26957 -5.9416 5.03457 5.014 14.479)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="ztq3aib9m"/><stop offset=".927" class="u8gjj--ww"/></radialGradient><radialGradient id="iWvTMLe" cx="0" cy="0" r="1" gradientTransform="matrix(.64063 0 0 1.11769 8.359 8.464)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="gxmlxwh_h"/><stop offset="1" class="xfa0_lr7b"/></radialGradient><radialGradient id="if442Wc" cx="0" cy="0" r="1" gradientTransform="matrix(.5 .0625 -.05841 .4673 8.788 9.604)" gradientUnits="userSpaceOnUse"><stop class="gxmlxwh_h"/><stop offset="1" class="xfa0_lr7b"/></radialGradient><radialGradient id="i4lzB8b" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .0235 -.02196 .49651 8.672 10.437)" gradientUnits="userSpaceOnUse"><stop class="gxmlxwh_h"/><stop offset="1" class="xfa0_lr7b"/></radialGradient><radialGradient id="iGk4akb" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .01562 -.0146 .49651 8.577 11.268)" gradientUnits="userSpaceOnUse"><stop class="gxmlxwh_h"/><stop offset="1" class="xfa0_lr7b"/></radialGradient><radialGradient id="iw5U1MQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.33688 0 0 -2.18001 11.352 6.46)" gradientUnits="userSpaceOnUse"><stop class="jicpa3bbs"/><stop offset="1" class="qfa6b6b9o"/></radialGradient><radialGradient id="iM9RMOc" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 4.21875 -4.50916 .36742 10.671 3.51)" gradientUnits="userSpaceOnUse"><stop class="gcbfxqthq"/><stop offset="1" class="l2exwdbrk"/></radialGradient><radialGradient id="iLMOe9c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.07393 1.0968 -1.36487 -5.0697 11.219 4.407)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="uf5twfbmg"/><stop offset="1" class="w0kxieb5j"/></radialGradient><radialGradient id="iyoJTkd" cx="0" cy="0" r="1" gradientTransform="rotate(97.469 1.378 9.352)scale(2.96582 1.73212)" gradientUnits="userSpaceOnUse"><stop class="ieqkgkbkd"/><stop offset=".828" class="qq-f_2hlv"/><stop offset=".954" class="ist11bcrw"/></radialGradient><radialGradient id="ihISGIh" cx="0" cy="0" r="1" gradientTransform="rotate(167.318 5.056 5.138)scale(.73517 .42203)" gradientUnits="userSpaceOnUse"><stop class="fs-1qm1fp"/><stop offset="1" class="gjcpth-fi"/></radialGradient><radialGradient id="i4rkiPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .91663 -2.06733 -.24668 9.202 8.945)" gradientUnits="userSpaceOnUse"><stop class="y6l47zr9z"/><stop offset=".26" class="ea4e01mlj"/><stop offset=".818" class="mg25f5b4x"/></radialGradient><radialGradient id="iCMgF9Y" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .1953 -.61632 -.27119 8.17 9.49)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="w5di5ljqj"/><stop offset="1" class="f4isb326x"/></radialGradient><radialGradient id="iXUqMWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .60156 -1.58152 0 8.929 10.768)" gradientUnits="userSpaceOnUse"><stop class="y6l47zr9z"/><stop offset=".26" class="ea4e01mlj"/><stop offset="1" class="mg25f5b4x"/></radialGradient><radialGradient id="iJYXnab" cx="0" cy="0" r="1" gradientTransform="matrix(-.16406 .9375 -2.12622 -.37208 9.14 9.807)" gradientUnits="userSpaceOnUse"><stop class="y6l47zr9z"/><stop offset=".26" class="ea4e01mlj"/><stop offset=".818" class="mg25f5b4x"/></radialGradient><radialGradient id="iShaEYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07813 .18158 -.5752 -.24748 8.148 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="w5di5ljqj"/><stop offset="1" class="f4isb326x"/></radialGradient><filter id="iE2ySnb" width="2.253" height="4.353" x="16.965" y="8.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.972549 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.486275 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7014" result="effect2_innerShadow_18_7014"/></filter><filter id="izaSGFd" width="5.313" height="3.969" x="15.515" y="21.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.878431 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7014" result="effect2_innerShadow_18_7014"/></filter><filter id="i6lsqkb" width="7.058" height="6.835" x="14.581" y="15.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.898039 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7014" result="effect2_innerShadow_18_7014"/></filter><filter id="ias1RQc" width="2.781" height="1.299" x="15.024" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.313726 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="iGx1AEd" width="3.004" height="1.261" x="18.084" y="15.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.384314 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="iOLsXmc" width="21.018" height="12.931" x="5.866" y="17.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8" dy=".15"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.45098 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="irx9MYb" width="2.168" height="2.566" x="6.458" y="18.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".2"/></filter><filter id="iIM4udd" width="3.72" height="9.463" x="7.036" y="11.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.52549 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="iojDlld" width=".953" height="1.923" x="9.804" y="8.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".1"/></filter><filter id="iqOwWTc" width="3.954" height="4.027" x="7.588" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.576471 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="i6S5Ckc" width="1.272" height="3.046" x="10.12" y="8.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="iGeTYxv" width="1.222" height="3.096" x="10.02" y="8.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7014"/></filter><filter id="iHR8Jje" width="7.904" height="4.958" x="9.216" y="25.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".1"/></filter><filter id="i1Ie6Ob" width="4.3" height="4.494" x="14.232" y="25.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".1"/></filter><filter id="ihEwM5b" width="3.383" height="4.304" x="16.522" y="25.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".2"/></filter><filter id="ixkZMOE" width="4.388" height="4.982" x="18.751" y="25.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".375"/></filter><filter id="iwwtDOV" width="4.564" height="4.128" x="21.056" y="26.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".2"/></filter><filter id="iQBCijn" width="3.62" height="3.685" x="5.95" y="21.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".25"/></filter><filter id="iM0EY6c" width="3.141" height="3.091" x="6.358" y="23.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".25"/></filter><filter id="iQF4b2p" width="3.885" height="4.584" x="6.776" y="25.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".2"/></filter><filter id="iwD2Amd" width="8.938" height="7.466" x="7.89" y="18.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7014" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:statue-of-liberty" /></template>
<style>
.a8o33yldj {
  d: path("m12.852 10.884l2.038 3.97l1.414-1.449l-2.891-2.926c-.282-.285-.744.05-.56.405");
}

.aefbndbvb {
  stop-color: var(--svg-color--acfaea, #ACFAEA);
}

.ag8g1gmqx {
  stop-color: var(--svg-color--325e4e, #325E4E);
  stop-opacity: 0;
}

.ah1qadbud {
  stop-color: var(--svg-color--18554c, #18554C);
  stop-opacity: 0;
}

.akputy45u {
  stop-color: var(--svg-color--6dd0bc, #6DD0BC);
}

.ay0flwb7z {
  d: path("M15.413 17.425c-.26.067-.893.543-1.343 1.906a33 33 0 0 0-.828 2.922c.405.658 1.482 1.963 2.937 2.694v-3.226h.89v-4.297z");
}

.b69fp-krl {
  stop-color: var(--svg-color--093024, #093024);
}

.bib5sfhjr {
  stop-color: var(--svg-color--14674d, #14674D);
}

.bn5095zay {
  stop-color: var(--svg-color--399478, #399478);
}

.bu89ge-mj {
  fill: var(--svg-color--195444, #195444);
  d: path("M6.859 18.813c.033.679.352 1.206.507 1.385l.86-.753c-.529-.753-1.408-1.48-1.367-.632");
}

.bwbodgcwv {
  fill-rule: evenodd;
  d: path("M10.581 29.901H9.416a71 71 0 0 1 2.403-1.386c.957-.512 2.264-1.22 3.008-1.777a60 60 0 0 1 1.972-1.381a.08.08 0 0 1 .094.006a.077.077 0 0 1 0 .117c-.353.29-.894.704-1.443 1.123c-.352.269-.707.54-1.018.783c-.319.249-.846.56-1.43.905c-.839.495-1.796 1.06-2.42 1.61");
}

.bz9b-y5wp {
  fill-rule: evenodd;
  d: path("M7.186 29.515c-.014-.264-.02-.56.025-.746a1.4 1.4 0 0 0 .035-.492c1.096-.891 2.91-2.385 3.015-2.547c-.352.7-1.426 2.351-3.075 3.785");
}

.c1on9ebya {
  fill-rule: evenodd;
  d: path("M25.22 29.823h-2.71l-1.047-3.155a.132.132 0 0 1 .215-.138z");
}

.c4icz31jr {
  d: path("m9.981 14.475l4.3 2.426l.656-1.89l-4.698-1.18c-.396-.1-.613.444-.258.644");
}

.c9jyatbxe {
  stop-color: var(--svg-color--2a7059, #2A7059);
  stop-opacity: 0;
}

.cmv7idbhl {
  stop-color: var(--svg-color--1e5f49, #1E5F49);
}

.cp95njb6g {
  stop-color: var(--svg-color--525c3f, #525C3F);
}

.cqgdrbcyc {
  fill-rule: evenodd;
  d: path("M6.762 24.582c-.08-.404-.12-.904-.16-1.39c-.035-.431-.07-.852-.13-1.184l-.022-.111c.222.215.568.38 1.089.354c.714-.035 1.186-.107 1.453-.168c.053-.012.103.07.065.109z");
}

.cwc53gb-h {
  stop-color: var(--svg-color--37816b, #37816B);
}

.cxi-mebpy {
  d: path("M7.28 8.792c-.037.255.172.5.301.562c.242-.12.871.098 1.16.18c.338.096.696-.02.665-.426c-.032-.406-.543-.59-1.063-.723c-.52-.132-.992-.066-1.062.407");
}

.d-7ljnbip {
  stop-color: var(--svg-color--56b8a5, #56B8A5);
}

.d055z9lap {
  d: path("M7.374 10.886c-.039-.29.145-.45.227-.485l.11-.258l.452-.066l.536.383c.131.023.392.141.382.425c-.009.285-.217.374-.32.383H7.82c-.149-.005-.406-.091-.446-.383");
}

.d2ssc9m9p {
  stop-color: var(--svg-color--92f2df, #92F2DF);
}

.d6on06wfv {
  stop-color: var(--svg-color--255a4f, #255A4F);
}

.dhggytx2e {
  stop-color: var(--svg-color--73c3b6, #73C3B6);
}

.dls505b1i {
  stop-color: var(--svg-color--325e4e, #325E4E);
}

.duyb3tbgu {
  stop-color: var(--svg-color--278a6c, #278A6C);
}

.e3gs-37ee {
  stop-color: var(--svg-color--3d9d8a, #3D9D8A);
}

.e4otybbbc {
  stop-color: var(--svg-color--525c3f, #525C3F);
  stop-opacity: 0;
}

.e8vsonbis {
  fill: var(--svg-color--2f7864, #2F7864);
  d: path("M15.413 17.425c-.26.067-.893.543-1.343 1.906a33 33 0 0 0-.828 2.922c.405.658 1.482 1.963 2.937 2.694v-3.226h.89v-4.297z");
}

.e99yiccgb {
  stop-color: var(--svg-color--6cd4bf, #6CD4BF);
  stop-opacity: 0;
}

.e9a9jtbsy {
  stop-color: var(--svg-color--2a7059, #2A7059);
}

.ea4e01mlj {
  stop-color: var(--svg-color--6fcebc, #6FCEBC);
}

.ehcb3yb9p {
  fill-rule: evenodd;
  d: path("M22.39 29.823H19.5l.73-3.254a.292.292 0 0 1 .547-.064z");
}

.er04-jy3v {
  d: path("M14.024 16.565a3.6 3.6 0 0 1 3.6-3.6h.722a3.6 3.6 0 0 1 3.6 3.6v2.641a.4.4 0 0 1-.4.4h-7.522z");
}

.f1ln1rb_x {
  stop-color: var(--svg-color--2c6964, #2C6964);
}

.f4isb326x {
  stop-color: var(--svg-color--00140e, #00140E);
  stop-opacity: 0;
}

.fs-1qm1fp {
  stop-color: var(--svg-color--7ce9d3, #7CE9D3);
}

.ft5dv1b6b {
  fill: none;
}

.g12sjob6v {
  stop-color: var(--svg-color--356d61, #356D61);
}

.g50s7ubyg {
  stop-color: var(--svg-color--1e5545, #1E5545);
}

.g77t_xbev {
  stop-color: var(--svg-color--8ef0dc, #8EF0DC);
  stop-opacity: 0;
}

.gcbfxqthq {
  stop-color: var(--svg-color--ffd43a, #FFD43A);
}

.ggqsyjbps {
  stop-color: var(--svg-color--599887, #599887);
  stop-opacity: 0;
}

.gjcpth-fi {
  stop-color: var(--svg-color--7ce9d3, #7CE9D3);
  stop-opacity: 0;
}

.gnqrzsbbr {
  stop-color: var(--svg-color--265b50, #265B50);
  stop-opacity: 0;
}

.gubo7nbof {
  stop-color: var(--svg-color--22584d, #22584D);
}

.guhf91kno {
  stop-color: var(--svg-color--3ea38b, #3EA38B);
  stop-opacity: 0;
}

.gxmlxwh_h {
  stop-color: var(--svg-color--1d382d, #1D382D);
}

.gz28-xb7v {
  stop-color: var(--svg-color--0b4033, #0B4033);
  stop-opacity: 0;
}

.h7riqn0di {
  stop-color: var(--svg-color--4c938b, #4C938B);
}

.hdvzz4bgp {
  stop-color: var(--svg-color--3fb69a, #3FB69A);
}

.hri9znbxc {
  d: path("M8.308 12.163c0-.426-.142-.715-.23-.777l2.578.39l-.079 6.516c0 1.34-.484 1.797-1 2.11c-.515.312-1.718.593-2.218 0c-.4-.476-.338-1.105-.282-1.407c.401-2.14 1.23-6.192 1.23-6.832");
}

.hu5k88bjf {
  d: path("m25.739 18.45l-4.7.568l.292-1.932l4.417.65c.415.062.407.664-.01.714");
}

.i5t2gib7w {
  d: path("M15.083 17.148c-.006.854-.015 2.137.16 3.252c.072.457.261.894.599 1.21c.481.45 1.14.848 1.819 1.125c.207.084.44.084.648 0c.68-.277 1.337-.675 1.819-1.125c.337-.316.526-.753.598-1.21c.175-1.115.166-2.398.16-3.252l-.001-.377c-1.192-.742-2.036-.807-2.9-.807");
}

.ibj47bx7y {
  d: path("M20.859 17.425c.15.114.4.38.5 1.03s1.03 5.68 1.484 8.071h-4v-1h1.234l-.156-3.969h-1.078V18.23z");
}

.ie5i73buq {
  stop-color: var(--svg-color--376e62, #376E62);
  stop-opacity: 0;
}

.ieqkgkbkd {
  stop-color: var(--svg-color--3d9f8d, #3D9F8D);
  stop-opacity: 0;
}

.irs5socky {
  stop-color: var(--svg-color--1c755d, #1C755D);
  stop-opacity: 0;
}

.ist11bcrw {
  stop-color: var(--svg-color--4cc2ab, #4CC2AB);
}

.iv1x16gyo {
  fill: var(--svg-color--4dbf9d, #4DBF9D);
  d: path("M20.859 17.425c.15.114.4.38.5 1.03s1.03 5.68 1.484 8.071h-4v-1h1.234l-.156-3.969h-1.078V18.23z");
}

.iwax-d_be {
  stop-color: var(--svg-color--7ee4cf, #7EE4CF);
  stop-opacity: 0;
}

.j0-txibgh {
  stop-color: var(--svg-color--87e2d1, #87E2D1);
}

.j4nb20b2f {
  stop-color: var(--svg-color--53cfb2, #53CFB2);
  stop-opacity: 0;
}

.j5f103boh {
  stop-color: var(--svg-color--51a69b, #51A69B);
}

.jh5c_du-q {
  stop-color: var(--svg-color--0b4033, #0B4033);
}

.jicpa3bbs {
  stop-color: var(--svg-color--b1fded, #B1FDED);
}

.jp7mejbpx {
  stop-color: var(--svg-color--1c5347, #1C5347);
}

.jyai5fbtt {
  stop-color: var(--svg-color--45a793, #45A793);
  stop-opacity: 0;
}

.k449cwboi {
  stop-color: var(--svg-color--236c5d, #236C5D);
  stop-opacity: 0;
}

.k8kvjw4cv {
  d: path("m17.63 9.252l-.615 4.055h1.953l-.646-4.058c-.063-.394-.632-.392-.692.003");
}

.kiga47jjh {
  stop-color: var(--svg-color--76c6b9, #76C6B9);
}

.kk07kc4ea {
  stop-color: var(--svg-color--a2f7e6, #A2F7E6);
}

.kx9cdabxu {
  stop-color: var(--svg-color--97f5e2, #97F5E2);
}

.kxmmr8ohx {
  stop-color: var(--svg-color--299774, #299774);
  stop-opacity: 0;
}

.kymqy9exi {
  stop-color: var(--svg-color--22584d, #22584D);
  stop-opacity: 0;
}

.l2exwdbrk {
  stop-color: var(--svg-color--e58615, #E58615);
}

.l2s911v2j {
  d: path("M21.78 16.234c.126.28.166.59.166.897v2.075a.4.4 0 0 1-.4.4h-7.522v-2.475c0-.307.04-.617.166-.897a4 4 0 0 1 3.647-2.356h.295a4 4 0 0 1 3.648 2.356");
}

.l47-ff88v {
  width: 5px;
  height: 1.945px;
  x: 7.015px;
  y: 6.112px;
  rx: 0.973px;
}

.l67868ovp {
  stop-color: var(--svg-color--45a793, #45A793);
}

.lkth9zbuf {
  stop-color: var(--svg-color--3ab697, #3AB697);
}

.lyt0vgkwo {
  d: path("m9.85 18.462l4.727.595l-.28-1.945l-4.452.637c-.416.059-.41.66.006.713");
}

.m8i0a5xfk {
  stop-color: var(--svg-color--1c755d, #1C755D);
}

.mephmkbvo {
  d: path("M10.27 10.432c-.208.387-.078.989-.02 1.106v.39l.304-.027c.475-.044.629-.52.629-.734l.055-.59a1.34 1.34 0 0 0-.118-.63a1.5 1.5 0 0 1-.124-.522c0-.375-.149-.57-.477-.54c-.328.032-.383.274-.398.75a1.8 1.8 0 0 0 .148.797");
}

.mg25f5b4x {
  stop-color: var(--svg-color--276758, #276758);
}

.mgufbdjop {
  fill: var(--svg-color--3fb297, #3FB297);
  d: path("M16.015 21.557h3.906l.156 3.97h-4.062z");
}

.mksqcidgm {
  stop-color: var(--svg-color--164d3b, #164D3B);
}

.mo6vmmbnk {
  stop-color: var(--svg-color--185040, #185040);
}

.ms7pevthj {
  d: path("M5.968 19.589c.238-1.025 1.179-1.852 1.606-2.102c.656-.12 1.953-.264 2.34-.234c.601.046 1.177.246 1.468.867c.291.62.242.71.492.984c.149.125.484.452 1.247 1.54c.927 1.412 2.287 2.72 3.312 3.58c.633.53 1.443.779 2.269.779h2.294c1.05 0 1.906.52 2.203.78c.39.287 1.356 1.038 2.094 1.75c.737.713.828 1.987.781 2.497H7.027c0-.234-.078-.902 0-1.23c.078-.329.063-.61-.156-1.282s.016-1.156 0-1.375s-.078-.594-.281-1.344s-.203-2.015-.344-2.796c-.14-.782-.575-1.133-.278-2.414");
}

.ms97-fb2l {
  stop-color: var(--svg-color--2d6253, #2D6253);
}

.mtkbwmb7u {
  d: path("M7.876 11.411c-.343-.07-.516-.399-.506-.56l1.46-.238v1.46h-.507c-.008-.18-.062-.584-.447-.662");
}

.mu-h0qb7f {
  d: path("M12.921 21.667c-.575-1.125-.969-1.922-1.406-2.078c-.651 1.167-1.328 1.843-2.625 2.359l2.625-.281c-.052.781.1 2.475 1.125 3s2.552.406 3.187.281c-.906-.562-2.187-1.875-2.906-3.281");
}

.mv5i1emhz {
  fill: var(--svg-color--023025, #023025);
  d: path("M10.421 10.632c-.417-.333-.449-1.01-.399-1.374c.012-.09.092-.15.182-.15a.2.2 0 0 1 .2.174l.154 1.108z");
}

.mwpl_9fpq {
  d: path("M7.882 7.842h.746v1.242h-.746z");
}

.mxfqq4b4d {
  stop-color: var(--svg-color--b6f0e3, #B6F0E3);
}

.mxh57b0xo {
  stop-color: var(--svg-color--296855, #296855);
}

.n0lp0zbgi {
  fill: var(--svg-color--49b3a0, #49B3A0);
  d: path("M10.27 10.432c-.208.387-.078.989-.02 1.106v.39l.304-.027c.475-.044.629-.52.629-.734l.055-.59a1.34 1.34 0 0 0-.118-.63a1.5 1.5 0 0 1-.124-.522c0-.375-.149-.57-.477-.54c-.328.032-.383.274-.398.75a1.8 1.8 0 0 0 .148.797");
}

.n8v8ybbkk {
  stop-color: var(--svg-color--18554c, #18554C);
}

.o-gvhvbrt {
  stop-color: var(--svg-color--43a78f, #43A78F);
}

.od-eadcqw {
  stop-color: var(--svg-color--8ef0dc, #8EF0DC);
}

.okwn0lbuv {
  d: path("m23.16 10.843l-1.856 3.693l-1.656-1.104l2.95-2.992c.28-.284.741.046.562.403");
}

.ow70ixnhn {
  stop-color: var(--svg-color--356d61, #356D61);
  stop-opacity: 0;
}

.oxedxck2g {
  stop-color: var(--svg-color--419a88, #419A88);
}

.p3u5lsz7v {
  stop-color: var(--svg-color--1c5347, #1C5347);
  stop-opacity: 0;
}

.p5oxbibrx {
  stop-color: var(--svg-color--256d5e, #256D5E);
}

.pak8nbczp {
  d: path("M15.85 16.159c-.373.16-.621.326-.789.552c-.08.11-.024.254.11.273c.374.055.991.009 1.406-.118c.632-.193.991-.54 1.198-.8c.065-.082.02-.195-.084-.202c-.439-.03-1.258.045-1.84.295");
}

.pix3gmy5p {
  stop-color: var(--svg-color--abf9e8, #ABF9E8);
  stop-opacity: 0;
}

.pjvt9itwd {
  stop-color: var(--svg-color--70d0bf, #70D0BF);
}

.pmbh4ubba {
  stop-color: var(--svg-color--135547, #135547);
  stop-opacity: 0;
}

.pnw_nc7ij {
  d: path("M16.015 21.557h3.906l.156 3.97h-4.062z");
}

.ppmqlzq3c {
  stop-color: var(--svg-color--1c4441, #1C4441);
}

.ps21kcb3d {
  stop-color: var(--svg-color--abf9e8, #ABF9E8);
}

.ps2fn8z6e {
  stop-color: var(--svg-color--50b5a1, #50B5A1);
}

.py9z2_kep {
  stop-color: var(--svg-color--4bb49d, #4BB49D);
  stop-opacity: 0;
}

.q3oq6vz9t {
  stop-color: var(--svg-color--3f7e76, #3F7E76);
}

.q5hee9bot {
  fill-rule: evenodd;
  d: path("M19.364 29.823h-2.442l2.064-3.37a.28.28 0 0 1 .519.158z");
}

.q9z5afz7o {
  stop-color: var(--svg-color--186e54, #186E54);
}

.qfa6b6b9o {
  stop-color: var(--svg-color--2b6a5e, #2B6A5E);
}

.qk3m-ijws {
  stop-color: var(--svg-color--3ea486, #3EA486);
}

.qkk--j2dj {
  stop-color: var(--svg-color--185040, #185040);
  stop-opacity: 0;
}

.qq-f_2hlv {
  stop-color: var(--svg-color--3d9f8d, #3D9F8D);
}

.r7fgf1bsx {
  stop-color: var(--svg-color--2d6e6a, #2D6E6A);
  stop-opacity: 0;
}

.r88z36bzg {
  stop-color: var(--svg-color--156b54, #156B54);
}

.rbokqcbmg {
  fill: var(--svg-color--4cc2ab, #4CC2AB);
  d: path("M8.308 12.163c0-.426-.142-.715-.23-.777l2.578.39l-.079 6.516c0 1.34-.484 1.797-1 2.11c-.515.312-1.718.593-2.218 0c-.4-.476-.338-1.105-.282-1.407c.401-2.14 1.23-6.192 1.23-6.832");
}

.ri62twb1m {
  stop-color: var(--svg-color--376e62, #376E62);
}

.rp_b4p_2t {
  fill: var(--svg-color--4dba9a, #4DBA9A);
  d: path("M20.097 16.131c.518.208.688.36.812.568c.07.119.01.265-.126.285c-.383.055-1.016.01-1.441-.118a2.4 2.4 0 0 1-1.227-.8a.124.124 0 0 1 .084-.206a4.45 4.45 0 0 1 1.898.271");
}

.rubefdb9l {
  stop-color: var(--svg-color--14674d, #14674D);
  stop-opacity: 0;
}

.rx_u74boy {
  stop-color: var(--svg-color--76dec7, #76DEC7);
}

.s_whom05g {
  stop-color: var(--svg-color--4fa096, #4FA096);
}

.s0lg6u3wb {
  stop-color: var(--svg-color--8dddd1, #8DDDD1);
}

.s98_46izs {
  stop-color: var(--svg-color--299774, #299774);
}

.sq_-5wb3n {
  stop-color: var(--svg-color--6cd4bf, #6CD4BF);
}

.ssraa9bhc {
  stop-color: var(--svg-color--54baa0, #54BAA0);
  stop-opacity: 0;
}

.stzz5qrfu {
  fill-rule: evenodd;
  d: path("M7.194 26.261v-.052c-.015-.218-.078-.593-.28-1.343a4 4 0 0 1-.056-.242l2.08-.452a.05.05 0 0 1 .048.082z");
}

.t033lobmd {
  d: path("M7.581 9.354c.21-.105.71.045 1.027.14l.134.04a.83.83 0 0 1 .414.242c.199.215.074.57-.13.66c-.138.061-.335.027-.554-.012a4 4 0 0 0-.316-.046a1.6 1.6 0 0 0-.547.03c-.102-.085-.387-.347-.336-.655c.01-.065.062-.305.308-.399");
}

.tcx1gh-5s {
  stop-color: var(--svg-color--93f3e0, #93F3E0);
}

.tf-a-kbst {
  stop-color: var(--svg-color--54baa0, #54BAA0);
}

.tfto-7-2d {
  stop-color: var(--svg-color--1b886e, #1B886E);
}

.tlp4qirvp {
  stop-color: var(--svg-color--93f3e0, #93F3E0);
  stop-opacity: 0;
}

.tt2hce02d {
  stop-color: var(--svg-color--3ea486, #3EA486);
  stop-opacity: 0;
}

.tujjnubop {
  stop-color: var(--svg-color--37816b, #37816B);
  stop-opacity: 0;
}

.tvtv-xbxs {
  stop-color: var(--svg-color--48b898, #48B898);
}

.u-lkfhbji {
  stop-color: var(--svg-color--388876, #388876);
  stop-opacity: 0;
}

.u10gt7bho {
  stop-color: var(--svg-color--70d8c5, #70D8C5);
}

.u76brdhhn {
  stop-color: var(--svg-color--4fb5a0, #4FB5A0);
}

.u7ws-3b1g {
  stop-color: var(--svg-color--4c938b, #4C938B);
  stop-opacity: 0;
}

.u8gjj--ww {
  stop-color: var(--svg-color--195d47, #195D47);
}

.uayrsd9sk {
  stop-color: var(--svg-color--5db9aa, #5DB9AA);
}

.ubwvvpb-g {
  stop-color: var(--svg-color--275548, #275548);
}

.uf5twfbmg {
  stop-color: var(--svg-color--bf6520, #BF6520);
  stop-opacity: 0;
}

.uhcz5gz0o {
  stop-color: var(--svg-color--95e8d9, #95E8D9);
}

.unfkv33te {
  stop-color: var(--svg-color--1b5547, #1B5547);
}

.v4ej81btm {
  stop-color: var(--svg-color--2d6e6a, #2D6E6A);
}

.vqgfefr-x {
  stop-color: var(--svg-color--8ce0d1, #8CE0D1);
}

.w-ln_ibdv {
  d: path("M7.589 4.893c-.02.707.268 1.107.414 1.219h2.96l.005-.005c.328-.398.836-1.016.082-2.339a7.3 7.3 0 0 0-1.216-1.592c-.192-.184-.472-.071-.553.182c-.15.47-.35.898-.552 1.14c-.036.042-.102.04-.14-.002l-.133-.147a.14.14 0 0 0-.216.003c-.259.319-.635.927-.651 1.541");
}

.w0kxieb5j {
  stop-color: var(--svg-color--bf6520, #BF6520);
}

.w4rh60b1o {
  stop-color: var(--svg-color--61b8a7, #61B8A7);
}

.w5di5ljqj {
  stop-color: var(--svg-color--00140e, #00140E);
}

.w5kf_ac1m {
  stop-color: var(--svg-color--388876, #388876);
}

.w7zg6sbbt {
  stop-color: var(--svg-color--265b50, #265B50);
}

.w8_jb8cly {
  stop-color: var(--svg-color--1e5545, #1E5545);
  stop-opacity: 0;
}

.wcqw_fbtw {
  stop-color: var(--svg-color--3ab697, #3AB697);
  stop-opacity: 0;
}

.we-9w0bxb {
  stop-color: var(--svg-color--599887, #599887);
}

.wef7g9ytd {
  stop-color: var(--svg-color--3ea38b, #3EA38B);
}

.wgyi1ea7k {
  d: path("m25.468 14.73l-3.758 2.148l-.505-1.841l4.009-.95c.393-.094.605.443.254.644");
}

.wnxh4obgu {
  stop-color: var(--svg-color--135547, #135547);
}

.wnyo68gca {
  d: path("M17.985 15.964c-.865 0-1.708.065-2.9.807l-.002.377");
}

.wtskyg7of {
  stop-color: var(--svg-color--4bb49d, #4BB49D);
}

.wx-8cltds {
  stop-color: var(--svg-color--236c5d, #236C5D);
}

.x0zahfb1g {
  stop-color: var(--svg-color--419a88, #419A88);
  stop-opacity: 0;
}

.xaqxb-gfg {
  stop-color: var(--svg-color--acfcec, #ACFCEC);
}

.xfa0_lr7b {
  stop-color: var(--svg-color--1d382d, #1D382D);
  stop-opacity: 0;
}

.xls2hrnga {
  stop-color: var(--svg-color--195546, #195546);
}

.xn9tf1b7s {
  stop-color: var(--svg-color--399478, #399478);
  stop-opacity: 0;
}

.xz11brxle {
  fill-rule: evenodd;
  d: path("M16.081 29.823h-1.65l3.657-4.048a.14.14 0 0 1 .225.163z");
}

.y16qbs0dv {
  stop-color: var(--svg-color--309076, #309076);
}

.y6l47zr9z {
  stop-color: var(--svg-color--89e8d6, #89E8D6);
}

.y8y_fh8gh {
  stop-color: var(--svg-color--53cfb2, #53CFB2);
}

.ya7_06mkz {
  stop-color: var(--svg-color--92f2df, #92F2DF);
  stop-opacity: 0;
}

.ybx6-ycvx {
  stop-color: var(--svg-color--2c6964, #2C6964);
  stop-opacity: 0;
}

.yh0rbb_bu {
  d: path("m8.698 14.625l-.277-6.661l1.985-.157l-.263 6.817a.5.5 0 0 1-.5.48h-.445a.5.5 0 0 1-.5-.479");
}

.yi194xrdy {
  stop-color: var(--svg-color--b6f0e3, #B6F0E3);
  stop-opacity: 0;
}

.zqsidabqj {
  fill: var(--svg-color--51a69b, #51A69B);
  d: path("m17.63 9.252l-.615 4.055h1.953l-.646-4.058c-.063-.394-.632-.392-.692.003");
}

.zt5vehnyl {
  stop-color: var(--svg-color--76dec7, #76DEC7);
  stop-opacity: 0;
}

.ztq3aib9m {
  stop-color: var(--svg-color--195d47, #195D47);
  stop-opacity: 0;
}

.zxv_msbpq {
  stop-color: var(--svg-color--164d3b, #164D3B);
  stop-opacity: 0;
}

</style>
