<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="iUuqrNN" width="20" height="24" x="6" y="6" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="rhg4ambly"/></mask><g class="ft5dv1b6b"><path fill="url(#ifiibic)" clip-rule="evenodd" class="he6lkcxbp"/><g filter="url(#iZ5ZNGt)"><path fill="url(#iIajE8b)" class="nogspqxym"/></g><g filter="url(#in6XOGe)"><path fill="url(#i9LmdCd)" class="qvi8_-1gp"/></g><path fill="url(#ivnexVc)" class="rhg4ambly"/><path fill="url(#iWE0HTb)" class="rhg4ambly"/><path fill="url(#i9qil1c)" class="rhg4ambly"/><path fill="url(#inTq14b)" class="rhg4ambly"/><g filter="url(#i1ttgPh)" mask="url(#iUuqrNN)"><path class="m-g7cdbrt"/></g><path fill="url(#iJ5xebd)" class="d3_c8bxzt"/><g filter="url(#i0e5nZc)"><path fill="url(#ibN08Ac)" class="lrjntrboc"/></g><path fill="url(#itnpiSb)" class="d3_c8bxzt"/><g filter="url(#iRuA9dd)"><path fill="url(#iuy89lU)" class="fyvh7jb7v"/></g><g filter="url(#i3W1Gxb)"><path fill="url(#iSZhw3b)" class="xz9dyvkwq"/></g><g filter="url(#i2CIrlR)"><path fill="url(#ikalYTd)" class="d4h1wubbf"/><path fill="url(#ikalYTd)" class="ghvhtkz-q"/><path fill="url(#ikalYTd)" class="qiqxisb7u"/><path fill="url(#ikalYTd)" class="a-__7wb3e"/><path fill="url(#ikalYTd)" class="krtf0kh5t"/><path fill="url(#ikalYTd)" class="rvgycxb_q"/></g><path fill="url(#iTVxg2b)" class="k-ndt6e5j"/><path fill="url(#ifiHpFe)" class="k-ndt6e5j"/><path fill="url(#iaStlEe)" class="k-ndt6e5j"/><path fill="url(#iX5LLDt)" class="d1lxu79pi"/><path fill="url(#iiygUbb)" class="d1lxu79pi"/><path fill="url(#iXb7ohe)" class="d1lxu79pi"/><path fill="url(#iB9i49b)" class="d7gieqbto"/><path fill="url(#ipQWjWb)" class="d7gieqbto"/><path fill="url(#iPfQWwd)" class="d7gieqbto"/><path fill="url(#iWVu7be)" class="l_717ib9l"/><path fill="url(#iSJ38Pb)" class="l_717ib9l"/><path fill="url(#i1VyGKd)" class="l_717ib9l"/><path fill="url(#iQ3TwED)" class="hcvhn9d_n"/><path fill="url(#ieE5JAw)" class="hcvhn9d_n"/><path fill="url(#ihCQOAI)" class="hcvhn9d_n"/><path fill="url(#i9nXNZd)" class="r06yfrbwj"/><path fill="url(#iFuqoPd)" class="r06yfrbwj"/><path fill="url(#icIliIe)" class="r06yfrbwj"/><g filter="url(#iC0UNpe)"><path fill="url(#ifnEvRb)" class="ggxp0xbkd"/></g><g filter="url(#irOGkfb)"><path fill="url(#iuyLO2d)" class="pktfqab0a"/></g><g filter="url(#i8Criqe)"><path fill="url(#icbxxSb)" class="as0ecm7pf"/></g><g filter="url(#iPyFiHc)"><path fill="url(#iUYAjWa)" class="s39ou7bxg"/></g><g filter="url(#ir8Nagd)"><path fill="url(#iLgZnWb)" class="abwl6rbqs"/></g><g filter="url(#iEuu1gc)"><path fill="url(#iHRMchc)" class="bsefdxbzd"/></g><defs><linearGradient id="ifiibic" x1="14.979" x2="16.979" y1="4.889" y2="4.887" gradientUnits="userSpaceOnUse"><stop class="ktl0jlhaf"/><stop offset="1" class="p2ti57b6a"/></linearGradient><linearGradient id="iIajE8b" x1="16.916" x2="16.916" y1="2.824" y2="6.502" gradientUnits="userSpaceOnUse"><stop class="cko0mj-vf"/><stop offset="1" class="pbbu_-v8m"/></linearGradient><linearGradient id="i9LmdCd" x1="15.916" x2="15.916" y1="2.824" y2="6.502" gradientUnits="userSpaceOnUse"><stop class="cko0mj-vf"/><stop offset="1" class="pbbu_-v8m"/></linearGradient><linearGradient id="inTq14b" x1="15.979" x2="15.979" y1="-16.225" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".49" class="ty8tubcfy"/><stop offset=".708" class="g1teekbnq"/></linearGradient><linearGradient id="iJ5xebd" x1="6.139" x2="25.809" y1="7.164" y2="11.44" gradientUnits="userSpaceOnUse"><stop class="wt2-b_b9a"/><stop offset="1" class="i_u09bb3e"/></linearGradient><linearGradient id="ibN08Ac" x1="7.924" x2="25.809" y1="7.462" y2="11.44" gradientUnits="userSpaceOnUse"><stop class="pb76vh1ma"/><stop offset="1" class="xg_g7yzsl"/></linearGradient><linearGradient id="iuy89lU" x1="6.7" x2="16.044" y1="11.255" y2="11.255" gradientUnits="userSpaceOnUse"><stop offset=".214" class="kf5qt7-3u"/><stop offset=".495" class="vda5j5b9h"/><stop offset="1" class="anom60b_f"/></linearGradient><linearGradient id="ikalYTd" x1="8.689" x2="20.39" y1="13.294" y2="26.372" gradientUnits="userSpaceOnUse"><stop class="k9i_7x6ki"/><stop offset="1" class="kcs9spb4x"/></linearGradient><linearGradient id="iTVxg2b" x1="11.869" x2="13.729" y1="19.535" y2="19.535" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="iX5LLDt" x1="18.239" x2="20.099" y1="19.535" y2="19.535" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="iB9i49b" x1="8.689" x2="10.549" y1="14.635" y2="14.635" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="iWVu7be" x1="15.059" x2="16.919" y1="14.635" y2="14.635" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="iQ3TwED" x1="15.059" x2="16.919" y1="24.085" y2="24.085" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="i9nXNZd" x1="21.439" x2="23.299" y1="14.635" y2="14.635" gradientUnits="userSpaceOnUse"><stop offset=".006" class="u3853kxcz"/><stop offset=".521" class="a4ra692ha"/><stop offset="1" class="es8pwejjc"/></linearGradient><linearGradient id="ifnEvRb" x1="10.498" x2="10.498" y1="13.986" y2="15.139" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><linearGradient id="iuyLO2d" x1="16.85" x2="16.85" y1="13.986" y2="15.139" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><linearGradient id="icbxxSb" x1="23.2" x2="23.2" y1="13.986" y2="15.139" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><linearGradient id="iUYAjWa" x1="20.05" x2="20.05" y1="18.9" y2="20.052" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><linearGradient id="iLgZnWb" x1="13.7" x2="13.7" y1="18.9" y2="20.052" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><linearGradient id="iHRMchc" x1="16.85" x2="16.85" y1="23.5" y2="24.652" gradientUnits="userSpaceOnUse"><stop class="z3k_xac4j"/><stop offset="1" class="egf81ck7g"/></linearGradient><radialGradient id="ivnexVc" cx="0" cy="0" r="1" gradientTransform="rotate(-161.001 15.236 7.092)scale(25.9623 22.0405)" gradientUnits="userSpaceOnUse"><stop class="qnpdn-b9p"/><stop offset=".583" class="z-nn9zbag"/><stop offset="1" class="jp5kdyb8s"/></radialGradient><radialGradient id="iWE0HTb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.86456 -18.70616 15.8804 -10.92123 31.87 34.294)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="c9k10ipgy"/><stop offset="1" class="yzog-bc6j"/></radialGradient><radialGradient id="i9qil1c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.45768 8.38976 -7.12243 -6.33115 21.367 13.972)" gradientUnits="userSpaceOnUse"><stop class="qbug9qbao"/><stop offset="1" class="ef-57rz9z"/></radialGradient><radialGradient id="itnpiSb" cx="0" cy="0" r="1" gradientTransform="matrix(11.9632 8.9724 -32.44242 43.25656 14.717 3.393)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="pucn5pbie"/><stop offset="1" class="aom2ihbpi"/></radialGradient><radialGradient id="iSZhw3b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50717 -2.6238 3.71005 -4.95914 25.412 11.025)" gradientUnits="userSpaceOnUse"><stop class="sz91j8bge"/><stop offset="1" class="htsde5y2r"/></radialGradient><radialGradient id="ifiHpFe" cx="0" cy="0" r="1" gradientTransform="rotate(46.797 -13.828 21.51)scale(3.52296 2.34864)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iaStlEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 14.37 21.96)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iiygUbb" cx="0" cy="0" r="1" gradientTransform="rotate(46.797 -10.643 28.87)scale(3.52296 2.34864)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iXb7ohe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 20.74 21.96)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="ipQWjWb" cx="0" cy="0" r="1" gradientTransform="matrix(2.41177 2.568 -1.712 1.60784 8.137 11.964)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iPfQWwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 11.19 17.06)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iSJ38Pb" cx="0" cy="0" r="1" gradientTransform="rotate(46.797 -6.571 22.746)scale(3.52296 2.34864)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="i1VyGKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 17.56 17.06)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="ieE5JAw" cx="0" cy="0" r="1" gradientTransform="rotate(46.797 -17.49 27.47)scale(3.52296 2.34864)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="ihCQOAI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 17.56 26.51)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iFuqoPd" cx="0" cy="0" r="1" gradientTransform="rotate(46.797 -3.381 30.118)scale(3.52296 2.34864)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="icIliIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33455 -2.54777 1.69851 -.8897 23.94 17.06)" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></radialGradient><filter id="iZ5ZNGt" width="1.7" height="5.128" x="15.566" y="1.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".3"/></filter><filter id="in6XOGe" width=".8" height="4.378" x="15.016" y="2.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".15"/></filter><filter id="i1ttgPh" width="20.67" height="6.44" x="5.639" y="5.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".25"/></filter><filter id="i0e5nZc" width="19.893" height="5.69" x="6.028" y="5.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".25"/></filter><filter id="iRuA9dd" width="9.723" height="2.655" x="6.5" y="8.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".1"/></filter><filter id="i3W1Gxb" width="7.444" height="5.703" x="18.718" y="6.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".375"/></filter><filter id="i2CIrlR" width="17.11" height="14.74" x="7.439" y="12.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".625"/></filter><filter id="iC0UNpe" width="1.3" height="2.452" x="9.348" y="13.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter><filter id="irOGkfb" width="1.3" height="2.452" x="15.7" y="13.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter><filter id="i8Criqe" width="1.3" height="2.452" x="22.05" y="13.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter><filter id="iPyFiHc" width="1.3" height="1.9" x="18.9" y="18.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter><filter id="ir8Nagd" width="1.3" height="1.9" x="12.55" y="18.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter><filter id="iEuu1gc" width="1.3" height="1.55" x="15.7" y="22.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28174" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:strawberry" /></template>
<style>
.a-__7wb3e {
  d: path("M15.06 14.67c0-.51.42-.93.93-.93s.93.41.93.93v.93c0 .51-.42.93-.93.93s-.93-.42-.93-.93z");
}

.a4ra692ha {
  stop-color: var(--svg-color--492368, #492368);
}

.abwl6rbqs {
  d: path("M13.45 18.9a.25.25 0 0 0-.5 0zm-.5.6a.25.25 0 1 0 .5 0zm0-.6v.6h.5v-.6z");
}

.anom60b_f {
  stop-color: var(--svg-color--e5ffbb, #E5FFBB);
  stop-opacity: 0.6;
}

.aom2ihbpi {
  stop-color: var(--svg-color--c1f57e, #C1F57E);
}

.as0ecm7pf {
  d: path("M22.95 13.986a.25.25 0 0 0-.5 0zm-.5 1.153a.25.25 0 0 0 .5 0zm0-1.153v1.153h.5v-1.153z");
}

.bsefdxbzd {
  d: path("M16.6 23.5a.25.25 0 0 0-.5 0zm-.5.25a.25.25 0 1 0 .5 0zm0-.25v.25h.5v-.25z");
}

.c9k10ipgy {
  stop-color: var(--svg-color--ff3555, #FF3555);
}

.cko0mj-vf {
  stop-color: var(--svg-color--c1eb79, #C1EB79);
}

.d1lxu79pi {
  d: path("M19.17 18.14c-.51 0-.93.42-.93.93V20c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.51-.41-.93-.93-.93");
}

.d3_c8bxzt {
  d: path("M6.14 11.44h5.54a5.43 5.43 0 0 0 4.296-2.103a5.43 5.43 0 0 0 4.293 2.103h5.54c0-3-2.43-5.44-5.44-5.44h-8.79c-3 0-5.44 2.44-5.44 5.44");
}

.d4h1wubbf {
  d: path("M9.62 13.74c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.52-.42-.93-.93-.93");
}

.d7gieqbto {
  d: path("M9.62 13.24c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.52-.42-.93-.93-.93");
}

.ef-57rz9z {
  stop-color: var(--svg-color--ff6399, #FF6399);
  stop-opacity: 0;
}

.egf81ck7g {
  stop-color: var(--svg-color--685475, #685475);
  stop-opacity: 0.6;
}

.es8pwejjc {
  stop-color: var(--svg-color--5a356b, #5A356B);
}

.ft5dv1b6b {
  fill: none;
}

.fyvh7jb7v {
  d: path("M15.999 9.265a.1.1 0 1 0-.152-.13zm-.152-.13c-1.303 1.523-2.653 2.02-3.738 2.02v.2c1.151 0 2.555-.529 3.89-2.09zm-3.738 2.02H6.7v.2h5.41z");
}

.g1teekbnq {
  stop-color: var(--svg-color--db3e60, #DB3E60);
  stop-opacity: 0;
}

.ggxp0xbkd {
  d: path("M10.248 13.986a.25.25 0 0 0-.5 0zm-.5 1.153a.25.25 0 0 0 .5 0zm0-1.153v1.153h.5v-1.153z");
}

.ghvhtkz-q {
  d: path("M11.87 19.57c0-.51.42-.93.93-.93c.52 0 .93.42.93.93v.93c0 .51-.42.93-.93.93s-.93-.42-.93-.93z");
}

.hcvhn9d_n {
  d: path("M15.99 22.69c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.51-.42-.93-.93-.93");
}

.he6lkcxbp {
  fill-rule: evenodd;
  d: path("M15.98 2a1 1 0 0 1 1 1v4.41a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1");
}

.htsde5y2r {
  stop-color: var(--svg-color--bef361, #BEF361);
  stop-opacity: 0;
}

.i_u09bb3e {
  stop-color: var(--svg-color--a4e726, #A4E726);
}

.jp5kdyb8s {
  stop-color: var(--svg-color--a3173d, #A3173D);
}

.k-ndt6e5j {
  d: path("M12.8 18.14c-.51 0-.93.42-.93.93V20c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.51-.41-.93-.93-.93");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k9i_7x6ki {
  stop-color: var(--svg-color--3a234a, #3A234A);
  stop-opacity: 0.6;
}

.kcs9spb4x {
  stop-color: var(--svg-color--3a234a, #3A234A);
  stop-opacity: 0.2;
}

.kf5qt7-3u {
  stop-color: var(--svg-color--9bbb67, #9BBB67);
  stop-opacity: 0;
}

.krtf0kh5t {
  d: path("M15.99 23.19c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.51-.42-.93-.93-.93");
}

.ktl0jlhaf {
  stop-color: var(--svg-color--74a41c, #74A41C);
}

.l_717ib9l {
  d: path("M15.99 13.24c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.52-.42-.93-.93-.93");
}

.lrjntrboc {
  d: path("M11.68 11.065H6.528a5.07 5.07 0 0 1 5.052-4.69h8.79a5.064 5.064 0 0 1 5.05 4.69h-5.15a5.06 5.06 0 0 1-3.998-1.958l-.296-.38l-.296.38a5.05 5.05 0 0 1-4 1.958");
}

.m-g7cdbrt {
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M6.14 11.44h5.54a5.43 5.43 0 0 0 4.296-2.103a5.43 5.43 0 0 0 4.293 2.103h5.54c0-3-2.43-5.44-5.44-5.44h-8.79c-3 0-5.44 2.44-5.44 5.44");
}

.nogspqxym {
  d: path("M16.666 2.824a.25.25 0 0 0-.5 0zm-.5 0v3.678h.5V2.824z");
}

.p2ti57b6a {
  stop-color: var(--svg-color--7caf1e, #7CAF1E);
}

.pb76vh1ma {
  stop-color: var(--svg-color--5e8317, #5E8317);
}

.pbbu_-v8m {
  stop-color: var(--svg-color--c1eb79, #C1EB79);
  stop-opacity: 0.4;
}

.pktfqab0a {
  d: path("M16.6 13.986a.25.25 0 0 0-.5 0zm-.5 1.153a.25.25 0 0 0 .5 0zm0-1.153v1.153h.5v-1.153z");
}

.pucn5pbie {
  stop-color: var(--svg-color--9ad03f, #9AD03F);
  stop-opacity: 0;
}

.qbug9qbao {
  stop-color: var(--svg-color--ff7d90, #FF7D90);
}

.qiqxisb7u {
  d: path("M18.24 19.57c0-.51.42-.93.93-.93c.52 0 .93.42.93.93v.93c0 .51-.42.93-.93.93s-.93-.42-.93-.93z");
}

.qnpdn-b9p {
  stop-color: var(--svg-color--ff3759, #FF3759);
}

.qvi8_-1gp {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.516 2.824a.1.1 0 0 0-.2 0zm-.2 0v3.678h.2V2.824z");
}

.r06yfrbwj {
  d: path("M22.37 13.24c-.51 0-.93.42-.93.93v.93c0 .51.42.93.93.93s.93-.42.93-.93v-.93c0-.52-.42-.93-.93-.93");
}

.rhg4ambly {
  d: path("m18.18 29.01l5.27-5.97c5.67-6.43 1.11-16.55-7.47-16.55S2.84 16.61 8.51 23.04l5.27 5.97a2.94 2.94 0 0 0 4.4 0");
}

.rvgycxb_q {
  d: path("M21.44 14.67c0-.51.42-.93.93-.93s.93.41.93.93v.93c0 .51-.42.93-.93.93s-.93-.42-.93-.93z");
}

.s39ou7bxg {
  d: path("M19.8 18.9a.25.25 0 1 0-.5 0zm-.5.6a.25.25 0 0 0 .5 0zm0-.6v.6h.5v-.6z");
}

.sz91j8bge {
  stop-color: var(--svg-color--dfffb6, #DFFFB6);
}

.ty8tubcfy {
  stop-color: var(--svg-color--6a1916, #6A1916);
}

.u3853kxcz {
  stop-color: var(--svg-color--3e2344, #3E2344);
}

.vda5j5b9h {
  stop-color: var(--svg-color--a7c873, #A7C873);
  stop-opacity: 0.6;
}

.wt2-b_b9a {
  stop-color: var(--svg-color--527515, #527515);
}

.xg_g7yzsl {
  stop-color: var(--svg-color--aee362, #AEE362);
}

.xz9dyvkwq {
  d: path("M25.412 11.025c-.589-3.56-3.186-4.203-3.186-4.203s-2.704 1.232-2.758 4.203z");
}

.yzog-bc6j {
  stop-color: var(--svg-color--ff3555, #FF3555);
  stop-opacity: 0;
}

.z-nn9zbag {
  stop-color: var(--svg-color--f01f60, #F01F60);
}

.z3k_xac4j {
  stop-color: var(--svg-color--685475, #685475);
}

</style>
