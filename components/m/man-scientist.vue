<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4GY69c)" class="sghpbcc-q"/><path fill="url(#iDPOTKd)" class="ox0t0tbyw"/><path fill="url(#izIfvad)" class="ox0t0tbyw"/><path fill="url(#ieAiHDe)" class="q6oyzpbgw"/><path fill="url(#i8s27wu)" class="q6oyzpbgw"/><path fill="url(#iEjhPFO)" class="q6oyzpbgw"/><path fill="url(#iIr2zNb)" class="q6oyzpbgw"/><path fill="url(#i6IymKc)" class="sx379zbqg"/><path fill="url(#icbfzYc)" class="sx379zbqg"/><path fill="url(#iD7xuyW)" class="sx379zbqg"/><path fill="url(#iokG4Xd)" class="sx379zbqg"/><g filter="url(#iGJ733c)"><path fill="url(#iPm6Z8c)" class="hjxoqcl0v"/></g><g filter="url(#iHGcaZc)"><path fill="url(#iBCBk6c)" class="hl1z6mh7m"/></g><g filter="url(#iP8U1ie)"><path fill="url(#iB7eXGc)" class="pdoe2nbxu"/></g><path fill="url(#igtP5Bj)" class="xrfastw7m"/><path fill="url(#iatXK9b)" class="xrfastw7m"/><path fill="url(#iHr6QPb)" class="xrfastw7m"/><path fill="url(#iFK6rod)" class="xrfastw7m"/><path fill="url(#iE99T7v)" class="xrfastw7m"/><path fill="url(#iziRMXb)" class="mx_0g-cbx"/><path fill="url(#iWWrm2c)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#iOYmIxc)" class="mx_0g-cbx"/><path fill="url(#ilQjMeb)" class="hl1z6mh7m"/><path fill="url(#iEtcdkc)" class="lceri-vrq"/><path fill="url(#iCnibBS)" class="lceri-vrq"/><path fill="url(#i4GY69c)" class="sghpbcc-q"/><path fill="url(#iSeXPEy)" class="ftb0dac9p"/><path class="kjivsy2zi"/><path fill="url(#isXCrGd)" class="gip5y3buk"/><path fill="url(#ixATofe)" class="a0q7e-rbb"/><path fill="url(#iIN33ps)" class="a0q7e-rbb"/><path fill="url(#iMD4Akd)" class="a0q7e-rbb"/><g filter="url(#iPwYgBm)"><rect class="rxsc4xb2z"/><rect fill="url(#iChxHKd)" class="q3ap7obeh"/><rect fill="url(#iEsINHM)" class="q3ap7obeh"/><rect fill="url(#imH7Vqd)" class="q3ap7obeh"/></g><path fill="url(#itN89Zb)" class="y_p91cc1i"/><path fill="url(#iJQA6ze)" class="y_p91cc1i"/><path fill="url(#iAFOnIe)" class="y_p91cc1i"/><path fill="url(#i4MNM9d)" class="y_p91cc1i"/><path fill="url(#idoLaid)" class="aokz37bnz"/><path fill="url(#iwOSsec)" class="uas9pu_nt"/><g filter="url(#iqnFYBe)"><path fill="url(#ibq2IZb)" class="muhausb9b"/><path fill="url(#izIWS5c)" class="muhausb9b"/><path fill="url(#ioQA9Ee)" class="muhausb9b"/><path fill="url(#iBa1lCd)" class="muhausb9b"/><path fill="url(#iZu7xIU)" class="muhausb9b"/></g><g filter="url(#ihQJVse)"><path stroke="url(#iznFBEb)" class="uk9cfxb_e"/></g><g filter="url(#iH1qFDU)"><path stroke="url(#iPzTIce)" class="f6mg-d1do"/></g><g filter="url(#i7gQTlc)"><path stroke="url(#iF9l4Ec)" class="oeasjrqnj"/></g><circle fill="url(#idispKe)" class="yjorey8ey"/><g filter="url(#i64FWEe)"><circle fill="url(#iOAGufd)" class="ic2f8cdzl"/></g><g filter="url(#iseTVeb)"><circle fill="url(#iQuWgCd)" class="urcxffbma"/><circle fill="url(#iXt7WeU)" class="urcxffbma"/></g><g filter="url(#iE9Zdmc)"><circle class="ypxpczbol"/><circle fill="url(#iikpbId)" class="r2srh5bmb"/><circle fill="url(#itODhJb)" class="r2srh5bmb"/></g><path fill="url(#iOI0mRb)" class="bme4fvtgp"/><path fill="url(#ixi8Vhe)" class="bme4fvtgp"/><path fill="url(#iPvnmST)" class="bme4fvtgp"/><path fill="url(#idpE8Yc)" class="bme4fvtgp"/><path fill="url(#ijSEJWd)" class="bme4fvtgp"/><g filter="url(#ixFTEYd)"><path class="gc_5b56ni"/><path fill="url(#imTVZyc)" class="w37e7vb7u"/><path fill="url(#i2qxAyf)" class="w37e7vb7u"/><path fill="url(#i9Pem0c)" class="w37e7vb7u"/><path fill="url(#iIvG6kb)" class="w37e7vb7u"/><path fill="url(#iDnO5Nc)" class="w37e7vb7u"/><path fill="url(#iVulKNc)" class="w37e7vb7u"/></g><path fill="url(#iD7Bvsd)" class="w37e7vb7u"/><path fill="url(#iK85Qyr)" class="w37e7vb7u"/><path fill="url(#ioNV2Zw)" class="w37e7vb7u"/><g filter="url(#iF2nYxd)"><path class="m1kfl35tx"/></g><g filter="url(#iUvuRic)"><path class="xrjp_hkzl"/><path fill="url(#iC6KDqe)" class="e5l7xqz2b"/><path fill="url(#iu9kFLe)" class="e5l7xqz2b"/><path fill="url(#ir95ZKe)" class="e5l7xqz2b"/></g><path fill="url(#imnRvdc)" class="e5l7xqz2b"/><g filter="url(#i30gnJb)"><path stroke="url(#iO4Mhte)" class="owcut5bcm"/></g><path class="e-zxp1bje"/><path class="reikhdcmh"/><path fill="url(#izgdxtw)" class="k013ptbyo"/><path class="xqexqtbsh"/><g filter="url(#iRiwbIj)"><path class="cjy2nzbdl"/><path fill="url(#ixJACFe)" class="hy1qyacdb"/></g><g filter="url(#i7b1m9c)"><path fill="url(#i98hTNs)" class="uicqgoa-y"/></g><path class="jgzcu8f_x"/><path fill="url(#ifoV7Mc)" class="k9q4sibel"/><path class="pz9w4tqer"/><g filter="url(#iqg0rhd)"><path fill="url(#iUbYoPb)" class="q-0q8bplt"/></g><g filter="url(#iik624c)"><ellipse transform="rotate(-27.914 12.867 9.932)" class="i0pljobpz"/><ellipse fill="url(#ia8lKUd)" transform="rotate(-27.914 12.867 9.932)" class="o4b_nhp5l"/></g><g filter="url(#ibo4hyb)"><path clip-rule="evenodd" class="qhwjvsbdg"/></g><g filter="url(#iIergee)"><path class="cmdpxjw1p"/></g><g filter="url(#iAJwCdd)"><path clip-rule="evenodd" class="i66fhe7nv"/></g><g filter="url(#igIzvzR)"><path class="tfb3qigln"/></g><path fill="url(#irjH29b)" class="dlpdj9bfs"/><g filter="url(#iFpmHRb)"><path clip-rule="evenodd" class="d32l4nd3w"/></g><defs><radialGradient id="iDPOTKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.317)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="izIfvad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.317)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="ieAiHDe" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.561)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="i6IymKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="igtP5Bj" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.692)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iatXK9b" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.308 -.254)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iHr6QPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 15.988)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="lwgxwcc9p"/><stop offset="1" class="brppywbtt"/></radialGradient><radialGradient id="iziRMXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.113)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="ilQjMeb" cx="0" cy="0" r="1" gradientTransform="rotate(109.374 .586 12.48)scale(3.01445 6.53104)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="hxg13bqik"/><stop offset="1" class="k10lreb3f"/></radialGradient><radialGradient id="iEtcdkc" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.879)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iSeXPEy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59837 5.09841 0 15.426 18.618)" gradientUnits="userSpaceOnUse"><stop class="yzv5f8bpf"/><stop offset=".621" class="p4jiy8bvo"/><stop offset="1" class="vj4_95wuu"/></radialGradient><radialGradient id="isXCrGd" cx="0" cy="0" r="1" gradientTransform="rotate(131.186 8.036 17.908)scale(.74743 .79607)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="iMD4Akd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.379)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="iChxHKd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.067)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="i4MNM9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.223)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="izIWS5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.454 24.582)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="ioQA9Ee" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.323 25.958)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iBa1lCd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.137 27.285)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iZu7xIU" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.041 28.552)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="idispKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.993 10.621)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iXt7WeU" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.56 10.356)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iikpbId" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.145 11.443)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="itODhJb" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.187 10.62)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iPvnmST" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 15.908 9.029)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="idpE8Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.765 9.349)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="ijSEJWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.203 9.315)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="imTVZyc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.113 2.9)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i9Pem0c" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 8.82 -1.65)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iIvG6kb" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 19.648 8.882)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iDnO5Nc" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 14.64 2.012)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iVulKNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 19.61 6.398)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iD7Bvsd" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.112 2.012)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iK85Qyr" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 11.03 3.274)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ioNV2Zw" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 16.57 6.253)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iO4Mhte" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.332 14.637)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="izgdxtw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93791 -1.10979 0 17.68 10.377)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixJACFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.24078 -.3103 .42719 -.3315 17.444 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifoV7Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93796 -1.10985 0 13.149 10.377)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ia8lKUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00803 -.51298 .61662 -.00965 12.851 10.259)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i4GY69c" x1="8.23" x2="22.659" y1="15.297" y2="15.297" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8s27wu" x1="11.239" x2="11.239" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iEjhPFO" x1="15.177" x2="14.208" y1="29.098" y2="29.098" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iD7xuyW" x1="19.74" x2="19.74" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iokG4Xd" x1="15.802" x2="16.505" y1="27.973" y2="27.973" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iPm6Z8c" x1="10.677" x2="12.896" y1="17.941" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iB7eXGc" x1="20.45" x2="18.099" y1="18.971" y2="23.672" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iFK6rod" x1="18.958" x2="17.552" y1="24.098" y2="22.598" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iE99T7v" x1="17.146" x2="17.974" y1="18.879" y2="19.223" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="iWWrm2c" x1="6.567" x2="6.567" y1="30.353" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iOYmIxc" x1="8.38" x2="7.935" y1="29.387" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iCnibBS" x1="22.753" x2="23.162" y1="27.66" y2="27.645" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixATofe" x1="23.825" x2="26.529" y1="20.848" y2="20.848" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iIN33ps" x1="26.529" x2="26.18" y1="20.832" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iJQA6ze" x1="26.529" x2="26.129" y1="23.309" y2="23.309" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iAFOnIe" x1="23.696" x2="24.227" y1="23.309" y2="23.309" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="idoLaid" x1="24.782" x2="23.892" y1="21.801" y2="21.801" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwOSsec" x1="24.782" x2="23.892" y1="23.582" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ibq2IZb" x1="27.165" x2="23.137" y1="28.051" y2="28.051" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iznFBEb" x1="25.435" x2="23.599" y1="25.99" y2="25.99" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iPzTIce" x1="25.356" x2="23.52" y1="27.295" y2="27.295" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iF9l4Ec" x1="25.435" x2="23.599" y1="28.6" y2="28.6" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iOAGufd" x1="10.664" x2="10.023" y1="10.9" y2="10.9" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iQuWgCd" x1="21.274" x2="20.455" y1="9.529" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iOI0mRb" x1="19.456" x2="11.813" y1="11.011" y2="12.15" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="ixi8Vhe" x1="10.016" x2="12.331" y1="13.71" y2="13.408" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i2qxAyf" x1="10.551" x2="13.456" y1="10.354" y2="5.194" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iC6KDqe" x1="14.552" x2="15.491" y1="11.671" y2="11.671" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iu9kFLe" x1="16.356" x2="15.329" y1="11.994" y2="11.979" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="ir95ZKe" x1="15.612" x2="15.612" y1="12.737" y2="12.163" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="imnRvdc" x1="15.543" x2="15.543" y1="12.779" y2="12.611" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="i98hTNs" x1="18.488" x2="18.162" y1="10.087" y2="10.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUbYoPb" x1="13.921" x2="13.595" y1="10.087" y2="10.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irjH29b" x1="10.917" x2="22.177" y1="9.6" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".609" class="khdfr5bqk"/><stop offset="1" class="cey6-nbgg"/></linearGradient><filter id="iGJ733c" width="7.023" height="11.703" x="8.591" y="15.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".375"/></filter><filter id="iHGcaZc" width="5.673" height="10.453" x="9.476" y="15.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="iP8U1ie" width="6.388" height="10.529" x="15.499" y="16.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".375"/></filter><filter id="iPwYgBm" width="4.008" height=".781" x="23.173" y="18.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="iqnFYBe" width="4.618" height="5.556" x="23.137" y="24.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="ihQJVse" width="2.047" height=".25" x="23.629" y="25.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="iH1qFDU" width="2.047" height=".25" x="23.551" y="27.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="i7gQTlc" width="2.047" height=".25" x="23.629" y="28.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="i64FWEe" width="2.992" height="2.992" x="9.168" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".25"/></filter><filter id="iseTVeb" width="3.592" height="3.592" x="18.516" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="iE9Zdmc" width="2.992" height="2.992" x="18.691" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".25"/></filter><filter id="ixFTEYd" width="12.614" height="8.301" x="9.11" y="1.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2165" result="effect2_innerShadow_4002_2165"/></filter><filter id="iF2nYxd" width="3.262" height="4.184" x="13.547" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".375"/></filter><filter id="iUvuRic" width="2.379" height="3.184" x="14.227" y="9.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".125"/></filter><filter id="i30gnJb" width="3.621" height="1.474" x="13.607" y="13.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="iRiwbIj" width=".809" height=".715" x="16.921" y="9.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="i7b1m9c" width=".91" height=".933" x="17.797" y="9.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".1"/></filter><filter id="iqg0rhd" width="1.009" height="1.065" x="13.184" y="9.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".1"/></filter><filter id="iik624c" width=".94" height=".724" x="12.397" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".05"/></filter><filter id="ibo4hyb" width="2.604" height="1.648" x="16.681" y="7.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482516 0 0 0 0 0.207378 0 0 0 0 0.109114 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="iIergee" width="2.709" height="1.503" x="16.629" y="7.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".2"/></filter><filter id="iAJwCdd" width="2.604" height="1.648" x="11.548" y="7.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482516 0 0 0 0 0.207378 0 0 0 0 0.109114 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/></filter><filter id="igIzvzR" width="2.709" height="1.503" x="11.495" y="7.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2165" stdDeviation=".2"/></filter><filter id="iFpmHRb" width="11.479" height="6.324" x="9.611" y="5.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2165"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2165" result="effect2_innerShadow_4002_2165"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist" /></template>
<style>
.a0q7e-rbb {
  d: path("M23.825 19.457h2.703v5.938h-2.703z");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aokz37bnz {
  d: path("M23.825 22.035v-.468h.805a.234.234 0 0 1 0 .468z");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bme4fvtgp {
  d: path("M10.312 10.008a30 30 0 0 1-.058-1.44c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.427 3.919-.427s3.275.266 3.92.427c.214.053.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.96c-.014.13-.055 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.213-3.006z");
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.brppywbtt {
  stop-color: var(--svg-color--f7ddd3, #F7DDD3);
  stop-opacity: 0;
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.cey6-nbgg {
  stop-color: var(--svg-color--c4c58e, #C4C58E);
  stop-opacity: 0.5;
}

.cjy2nzbdl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.614 9.732c.066.088-.072.196-.23.313c-.156.117-.272.2-.338.112s.007-.255.164-.373s.338-.14.404-.052");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cmdpxjw1p {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.813 8.207c-.21-.193-.803-.52-1.659-.44");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d32l4nd3w {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.042c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.567-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dlpdj9bfs {
  d: path("M18.083 6.337h-5.275c-1.497 0-2.737 1.2-2.746 2.707a2.72 2.72 0 0 0 2.716 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e-zxp1bje {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.417 13.754c-.508 0-.985-.12-1.387-.328c-.137-.07-.284.084-.198.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e5l7xqz2b {
  d: path("m15.034 10.336l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.115-.377-.646-.377-.766 0");
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f6mg-d1do {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.676 27.295h1.797");
}

.ft5dv1b6b {
  fill: none;
}

.ftb0dac9p {
  d: path("M15.426 18.618a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gc_5b56ni {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.261.526-.573.534c.036-.504.069-1.318.082-1.446c.043-.434-.025-.561-.422-.956c-.215-.214-.376-.534-.376-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.918.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.761c.014.156.035 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hjxoqcl0v {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.637l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38c0-.283-.06-.562-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.256");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hl1z6mh7m {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .085.248l-.626.692a.5.5 0 0 0 .014.686L14.656 26a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.255");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hxg13bqik {
  stop-color: var(--svg-color--b7938b, #B7938B);
}

.hy1qyacdb {
  d: path("M17.614 9.732c.066.088-.072.196-.23.313c-.156.117-.272.2-.338.112s.007-.255.164-.373s.338-.14.404-.052");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i0pljobpz {
  cx: 12.867px;
  cy: 9.932px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.405px;
  ry: 0.205px;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i66fhe7nv {
  fill: var(--svg-color--984426, #984426);
  fill-rule: evenodd;
  d: path("M13.636 8.348c-.72-.067-1.183.214-1.295.317a.473.473 0 0 1-.64-.695c.306-.282 1.032-.656 2.022-.563a.473.473 0 1 1-.088.941");
}

.ic2f8cdzl {
  cx: 10.664px;
  cy: 10.621px;
  r: 0.996px;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.jgzcu8f_x {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.932 9.254a1.45 1.45 0 0 0-1.407 1.099a.285.285 0 0 0 .278.354h2.317a.24.24 0 0 0 .236-.283a1.455 1.455 0 0 0-1.424-1.17");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.k013ptbyo {
  d: path("M17.682 9.536a.927.927 0 0 1 .893 1.17h-1.79a.93.93 0 0 1 .897-1.17");
}

.k10lreb3f {
  stop-color: var(--svg-color--d8c4c9, #D8C4C9);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.k9q4sibel {
  d: path("M13.147 9.536a.927.927 0 0 0-.893 1.17h1.79a1 1 0 0 0 .033-.244a.933.933 0 0 0-.93-.926");
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.khdfr5bqk {
  stop-color: var(--svg-color--c4c58e, #C4C58E);
}

.kjivsy2zi {
  fill: var(--svg-color--ffd335, #FFD335);
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lwgxwcc9p {
  stop-color: var(--svg-color--ebd4c9, #EBD4C9);
}

.m1kfl35tx {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.141 10.5l-.82 1.7c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.284-.378-.396 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.muhausb9b {
  d: path("M23.137 25.314c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.o4b_nhp5l {
  cx: 12.867px;
  cy: 9.932px;
  rx: 0.405px;
  ry: 0.205px;
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

.oeasjrqnj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 28.6h1.797");
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.owcut5bcm {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.417 13.754c-.508 0-.985-.12-1.387-.328c-.137-.07-.284.084-.198.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33Z");
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4jiy8bvo {
  stop-color: var(--svg-color--d48028, #D48028);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pdoe2nbxu {
  d: path("m21.02 18.142l.115 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.61a.44.44 0 0 1-.012.608l-4.188 4.255a.177.177 0 0 1-.303-.124V22.89c0-.25.053-.496.155-.724l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pz9w4tqer {
  fill: var(--svg-color--000, #000);
  d: path("M13.677 10.463a.53.53 0 0 0-.53-.531a.528.528 0 0 0-.472.775h.94a.5.5 0 0 0 .062-.245");
}

.q-0q8bplt {
  d: path("M13.993 10.354c0-.3-.243-.5-.309-.56l-.3.29l.185.375z");
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q3ap7obeh {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  rx: 0.391px;
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q6oyzpbgw {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453V23.47z");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qhwjvsbdg {
  fill: var(--svg-color--984426, #984426);
  fill-rule: evenodd;
  d: path("M17.198 8.348c.72-.067 1.183.214 1.295.317a.473.473 0 1 0 .64-.695c-.306-.282-1.032-.656-2.023-.563a.473.473 0 0 0 .088.941");
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r2srh5bmb {
  cx: 20.187px;
  cy: 10.621px;
  r: 0.996px;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.reikhdcmh {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.897 9.254c.678 0 1.25.467 1.406 1.099a.285.285 0 0 1-.278.354H16.71a.24.24 0 0 1-.236-.283a1.45 1.45 0 0 1 1.424-1.17");
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rxsc4xb2z {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sghpbcc-q {
  d: path("M15.466 15.298h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.sx379zbqg {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98V23.47z");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tfb3qigln {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.02 8.207c.21-.193.804-.52 1.66-.44");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.uas9pu_nt {
  d: path("M23.825 23.817v-.47h.805a.234.234 0 1 1 0 .47z");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.uicqgoa-y {
  d: path("M18.507 10.34a.87.87 0 0 0-.24-.48l-.27.296l.122.237z");
}

.uk9cfxb_e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 25.99h1.797");
}

.urcxffbma {
  cx: 20.187px;
  cy: 10.621px;
  r: 1.671px;
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vj4_95wuu {
  stop-color: var(--svg-color--a15002, #A15002);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w37e7vb7u {
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.261.526-.573.534c.036-.504.069-1.318.082-1.446c.043-.434-.025-.561-.422-.956c-.215-.214-.376-.534-.376-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.918.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.761c.014.156.035 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xqexqtbsh {
  fill: var(--svg-color--000, #000);
  d: path("M17.151 10.462c0-.294.236-.53.53-.53a.528.528 0 0 1 .473.775h-.94a.5.5 0 0 1-.063-.245");
}

.xrfastw7m {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.692a.5.5 0 0 1-.014.686L16.323 26a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.298 1.807.722 2.61 1.255");
}

.xrjp_hkzl {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.034 10.336l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.115-.377-.646-.377-.766 0");
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y_p91cc1i {
  d: path("M26.529 21.223v4.172h-2.704v-4.172z");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.yjorey8ey {
  cx: 10.664px;
  cy: 10.621px;
  r: 1.671px;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ypxpczbol {
  cx: 20.187px;
  cy: 10.621px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.yzv5f8bpf {
  stop-color: var(--svg-color--e69b19, #E69B19);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
