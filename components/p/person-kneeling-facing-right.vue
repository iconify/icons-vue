<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4Uc2MV)"><path class="v01ntrb1u"/></g><g filter="url(#inD5aWt)"><path stroke="url(#iK3kyme)" class="ckdeyfb5o"/></g><path fill="url(#iVvMvhc)" class="g_li9-ihr"/><g filter="url(#iujFMGc)"><path class="lhnr57wmq"/></g><path fill="url(#iTJ04ce)" class="ac_tq7baf"/><path fill="url(#iH8PZYd)" class="ac_tq7baf"/><path fill="url(#iGGGiHc)" class="h54ak-baq"/><g filter="url(#iaMt5Ed)"><path class="dxtr3x04o"/><path fill="url(#i0r7beb)" class="i_9xn53pt"/><path fill="url(#isgHxFe)" class="i_9xn53pt"/></g><g filter="url(#iWML08b)"><path class="n47z523pv"/><path fill="url(#iUdzqxe)" class="l_7786bhe"/><path fill="url(#iUG6ZNu)" class="l_7786bhe"/></g><path fill="url(#iEGXTAc)" transform="scale(-1 1)rotate(-14.867 34.912 75.153)" class="ofkpelbcu"/><path fill="url(#i2xqcwd)" transform="scale(-1 1)rotate(-14.867 34.912 75.153)" class="ofkpelbcu"/><path fill="url(#iJwwmDb)" class="pej1jacmd"/><path fill="url(#iIhIaze)" class="pej1jacmd"/><path fill="url(#i5jGM5d)" class="pej1jacmd"/><path fill="url(#igQWCAb)" class="iji0xeufm"/><g filter="url(#iXDTSBe)"><path fill="url(#iEiFU5c)" class="ortjz6b5c"/><path fill="url(#i7cJAge)" class="ortjz6b5c"/></g><g filter="url(#i1n72Rd)"><path class="kw0zq2_4j"/><path fill="url(#iBciucc)" class="ww67aix3d"/><path fill="url(#izVbU7b)" class="ww67aix3d"/><path fill="url(#iQfpzdb)" class="ww67aix3d"/><path fill="url(#ivAP5Md)" class="ww67aix3d"/><path fill="url(#iuGEPab)" class="ww67aix3d"/></g><path fill="url(#ihaSKBo)" class="nb644jbwo"/><path clip-rule="evenodd" class="ekg_obblt"/><g filter="url(#iEHejTd)"><path clip-rule="evenodd" class="tz9z4acqy"/></g><path class="voa8xp4wr"/><path fill="url(#iFwyoBb)" class="pndc1ghge"/><path fill="url(#iO5fHcM)" class="tyzruxn8y"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -30.938 -39.285)" class="m1l7k9jve"/><g filter="url(#i8t9rit)"><path class="kucha2b0z"/><path fill="url(#iBcdbsa)" class="k13p5huei"/></g><g filter="url(#iyT3BDb)"><path class="pn2ugybry"/></g><g filter="url(#ilgI46c)"><path class="v2xs5vv8x"/></g><path fill="url(#iXxwqSM)" class="jap_2qbrm"/><path fill="url(#i96NNCe)" class="jap_2qbrm"/><path fill="url(#ipV5u9b)" class="jap_2qbrm"/><path fill="url(#iiiL4vb)" class="jap_2qbrm"/><g filter="url(#i31lPvb)"><path fill="url(#i6vHs7d)" class="jz3a-dbmp"/></g><defs><radialGradient id="iK3kyme" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.508 10.67)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iVvMvhc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 22.277)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iH8PZYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 19.948)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iGGGiHc" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.557 20.058)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iEGXTAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop class="v1jncd8lo"/><stop offset="1" class="dk759-bpk"/></radialGradient><radialGradient id="i2xqcwd" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="zx9q0nboq"/><stop offset="1" class="o8lmzhb1s"/></radialGradient><radialGradient id="iJwwmDb" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 15.574)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="zgjycebbf"/><stop offset=".849" class="cic7ureox"/></radialGradient><radialGradient id="iIhIaze" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.76 13.7)" gradientUnits="userSpaceOnUse"><stop class="pyqlo9ccb"/><stop offset="1" class="tim0t4m8u"/></radialGradient><radialGradient id="i5jGM5d" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.837 17.322)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="xu4oisaxz"/><stop offset="1" class="jtmbyac_e"/></radialGradient><radialGradient id="igQWCAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5142 .9576 -1.21956 -.65485 20.422 9.74)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="i7cJAge" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.681 9.678)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iBciucc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90805 -1.94145 2.83721 -2.78841 16.199 11.113)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="izVbU7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 .89062 -1.25031 2.9832 14.79 7.451)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iQfpzdb" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.23437 .10899 .37782 14.838 10.654)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="ivAP5Md" cx="0" cy="0" r="1" gradientTransform="matrix(1.79688 .32813 -.1515 .82965 16.424 6.092)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="iuGEPab" cx="0" cy="0" r="1" gradientTransform="matrix(-.50781 .47657 -.68826 -.73338 19.337 6.007)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="ihaSKBo" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 16.469 9.498)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iFwyoBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.045 9.752)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iO5fHcM" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.213 9.773)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iBcdbsa" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.04687 -1.5625 0 15.603 17.697)" gradientUnits="userSpaceOnUse"><stop class="m8h2-hfui"/><stop offset="1" class="q2n0f68xb"/></radialGradient><radialGradient id="iXxwqSM" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.5625 2.32707 .11157 17.09 17.37)" gradientUnits="userSpaceOnUse"><stop class="q-nbb5ezw"/><stop offset="1" class="jqsx2jbza"/></radialGradient><radialGradient id="i96NNCe" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.32812 -1.6478 1.08562 15.432 13.433)" gradientUnits="userSpaceOnUse"><stop class="eq7ur_bkf"/><stop offset="1" class="uverm5y1q"/></radialGradient><filter id="i4Uc2MV" width="7.28" height="8.609" x="10.996" y="21.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1848" result="effect2_innerShadow_2_1848"/></filter><filter id="inD5aWt" width="5.734" height="7.279" x="11.071" y="22.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1848" stdDeviation=".25"/></filter><filter id="iujFMGc" width="11.64" height="10.135" x="13.28" y="19.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="iaMt5Ed" width="4.352" height="2.364" x="20.218" y="27.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="iWML08b" width="3.579" height="3.542" x="7.83" y="26.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="iXDTSBe" width="4.443" height="5.249" x="15.413" y="7.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="i1n72Rd" width="5.586" height="5.499" x="14.291" y="5.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="iEHejTd" width="1.013" height=".568" x="18.181" y="8.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="i8t9rit" width="6.876" height="3.179" x="15.419" y="17.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="iyT3BDb" width="1.171" height="1.539" x="21.358" y="18.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="ilgI46c" width="1.196" height="1.065" x="20.878" y="19.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1848"/></filter><filter id="i31lPvb" width="8.168" height="8.42" x="14.276" y="20.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1848" stdDeviation=".375"/></filter><linearGradient id="iTJ04ce" x1="15.214" x2="15.214" y1="19.855" y2="20.386" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="i0r7beb" x1="20.089" x2="21.073" y1="29.12" y2="29.12" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="isgHxFe" x1="21.526" x2="21.526" y1="29.984" y2="29.613" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iUdzqxe" x1="11.064" x2="10.378" y1="27.073" y2="27.738" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iUG6ZNu" x1="8.917" x2="9.132" y1="28.277" y2="28.448" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iEiFU5c" x1="16.994" x2="19.856" y1="10.42" y2="10.592" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ipV5u9b" x1="15.886" x2="15.979" y1="17.542" y2="16.292" gradientUnits="userSpaceOnUse"><stop class="ky5pzdbbm"/><stop offset="1" class="giu-ixb2s"/></linearGradient><linearGradient id="iiiL4vb" x1="18.245" x2="17.393" y1="17.253" y2="17.253" gradientUnits="userSpaceOnUse"><stop class="uk2nrwb0k"/><stop offset="1" class="uy34yibrn"/></linearGradient><linearGradient id="i6vHs7d" x1="21.694" x2="15.214" y1="26.87" y2="20.933" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-kneeling-facing-right" /></template>
<style>
.ac_tq7baf {
  d: path("M22.764 23.152c-.137.575-.807 3.427-1.125 4.78c.573.233 1.39.67 2.067 1.009c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079a2.726 2.726 0 0 1 1.874 3.125");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.cic7ureox {
  stop-color: var(--svg-color--e54d24, #E54D24);
}

.ckdeyfb5o {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 22.636c.138.941.573 3.263 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.085c-.689-.243-2.053-.526-3.737-.302");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dk759-bpk {
  stop-color: var(--svg-color--ffcc40, #FFCC40);
}

.dxtr3x04o {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 28.561a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.ekg_obblt {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M18.577 10.887a.125.125 0 0 0 .001.177c.238.233.583.293.692.304a.125.125 0 1 0 .026-.248c-.094-.01-.367-.062-.543-.235a.125.125 0 0 0-.177.002");
}

.eq7ur_bkf {
  stop-color: var(--svg-color--ff9337, #FF9337);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.g_li9-ihr {
  d: path("M17.27 27.66c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.14 2.372.086 2.43-2.047");
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.giu-ixb2s {
  stop-color: var(--svg-color--ef6623, #EF6623);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.h54ak-baq {
  d: path("M20.293 22.565v-.003c-1.787.442-3.937.808-5.747.261c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079c.267.09.5.205.701.336z");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i_9xn53pt {
  d: path("M20.23 28.561a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.iji0xeufm {
  d: path("M20.052 9.943a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.175.02-.394-.176-.578");
}

.jap_2qbrm {
  d: path("M17.724 14.656a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jqsx2jbza {
  stop-color: var(--svg-color--ff8130, #FF8130);
}

.jtmbyac_e {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
}

.jz3a-dbmp {
  d: path("m21.683 22.488l-.657 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.274-1.094-.649c1.193-.01 4.677-.024 5.664 0c.988.026 1.04.863.992 1.29");
}

.k13p5huei {
  d: path("m17.315 18.12l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.215c.038-.19-.39-.567-.79-.71c-1.254-.45-2.96-.82-3.988-.95");
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kucha2b0z {
  fill: var(--svg-color--ffbf36, #FFBF36);
  d: path("m17.315 18.12l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.215c.038-.19-.39-.567-.79-.71c-1.254-.45-2.96-.82-3.988-.95");
}

.kw0zq2_4j {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M19.767 6.637c-.237-.487-.796-.603-1.074-.588c-.86.047-.977.344-1.754.183c-.821-.169-1.226-.12-1.578.04l-.007.003c-.346.157-1.063.483-1.063 1.95c0 1.351.482 2.065.715 2.32l-.046.017c-.232.083-.327.33-.244.561c.072.198.322.311.637.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.244V9.88c0-.469.33-.749.476-.832c.016-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.157c1.015-.061 1.312-.821 1.015-1.43");
}

.ky5pzdbbm {
  stop-color: var(--svg-color--f04d1d, #F04D1D);
}

.l_7786bhe {
  d: path("m10.524 26.808l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.066-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.lhnr57wmq {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 23.152c-.137.575-.807 3.427-1.125 4.78c.573.233 1.39.67 2.067 1.009c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.079a2.726 2.726 0 0 1 1.874 3.125");
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m8h2-hfui {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
}

.n47z523pv {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 26.808l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.066-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nb644jbwo {
  d: path("M17.059 10.44c.05 0 .085-.047.078-.097l-.173-1.248c-.007-.056-.059-.095-.112-.079a.727.727 0 0 0 .207 1.424");
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o8lmzhb1s {
  stop-color: var(--svg-color--d8952d, #D8952D);
  stop-opacity: 0;
}

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.ortjz6b5c {
  d: path("M19.828 8.98c-.038-.802-.298-1.188-.42-1.3h-3.732l-.063 3.163c.867 2.122 3.512 2.213 3.907 1.445c.395-.767.353-2.38.308-3.308");
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pej1jacmd {
  d: path("M18.323 15.171c.162 1.15.094 2.637-.016 3.528v1.289h-5.031c.055-2.063.578-4.729 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.605.183 1.422.75 1.625 2.187");
}

.pn2ugybry {
  fill: var(--svg-color--eeae2f, #EEAE2F);
  d: path("m21.401 19.19l-.043.633c.233.182.452.428.603.609a.27.27 0 0 0 .346.058a.243.243 0 0 0 .085-.338a3.6 3.6 0 0 0-.99-.961");
}

.pndc1ghge {
  d: path("M18.717 9.773V9.77c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.003z");
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pyqlo9ccb {
  stop-color: var(--svg-color--ff953a, #FF953A);
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q-nbb5ezw {
  stop-color: var(--svg-color--ea5e20, #EA5E20);
}

.q2n0f68xb {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
  stop-opacity: 0;
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.tim0t4m8u {
  stop-color: var(--svg-color--ff953a, #FF953A);
  stop-opacity: 0;
}

.tyzruxn8y {
  d: path("m18.912 9.773l-.004-.072c0-.185.079-.336.176-.336s.175.15.175.336l-.004.072z");
}

.tz9z4acqy {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M18.81 8.74a.8.8 0 0 1 .216-.015a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.173a.15.15 0 0 0 .178.24c.085-.062.19-.1.29-.12");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk2nrwb0k {
  stop-color: var(--svg-color--d36030, #D36030);
}

.uverm5y1q {
  stop-color: var(--svg-color--ff9337, #FF9337);
  stop-opacity: 0;
}

.uy34yibrn {
  stop-color: var(--svg-color--d36030, #D36030);
  stop-opacity: 0;
}

.v01ntrb1u {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M17.27 27.66c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.14 2.372.086 2.43-2.047");
}

.v1jncd8lo {
  stop-color: var(--svg-color--e8912c, #E8912C);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v2xs5vv8x {
  fill: var(--svg-color--f6b22f, #F6B22F);
  d: path("M21.448 19.788c-.325-.003-.516.179-.57.27c.271.144.499.376.65.567c.1.124.278.169.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.533");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.voa8xp4wr {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.322 9.773h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.ww67aix3d {
  d: path("M19.767 6.637c-.237-.487-.796-.603-1.074-.588c-.86.047-.977.344-1.754.183c-.821-.169-1.226-.12-1.578.04l-.007.003c-.346.157-1.063.483-1.063 1.95c0 1.351.482 2.065.715 2.32l-.046.017c-.232.083-.327.33-.244.561c.072.198.322.311.637.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.244V9.88c0-.469.33-.749.476-.832c.016-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.157c1.015-.061 1.312-.821 1.015-1.43");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xu4oisaxz {
  stop-color: var(--svg-color--cd5a3b, #CD5A3B);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.zgjycebbf {
  stop-color: var(--svg-color--ff6e34, #FF6E34);
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zx9q0nboq {
  stop-color: var(--svg-color--d8952d, #D8952D);
}

</style>
