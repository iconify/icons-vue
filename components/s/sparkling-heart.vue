<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuotm1c)" class="rt_h9bbqs"/><path fill="url(#iTpVKIb)" class="rt_h9bbqs"/><path fill="url(#iisXlLe)" class="rt_h9bbqs"/><path fill="url(#iXzGJJe)" class="rt_h9bbqs"/><path fill="url(#ivlvtgd)" class="rt_h9bbqs"/><path fill="url(#iAW3Pfb)" class="rt_h9bbqs"/><path fill="url(#ijHt4yd)" class="p_568nbdw"/><g filter="url(#i5EJwQi)"><path class="r5vwmjb7p"/></g><g filter="url(#i0xy92b)"><ellipse fill="url(#i2xsxVc)" transform="rotate(-44.19 24.707 11.581)" class="u67yf7bje"/></g><g filter="url(#iwV5l9b)"><ellipse fill="url(#idTTIWd)" transform="rotate(-128.955 12.467 11.187)" class="v0kxk-buz"/></g><g filter="url(#iCqoC4b)"><path class="os35pryth"/></g><path fill="url(#iC0TsBc)" class="m7s_qpbap"/><path fill="url(#i49461E)" class="m7s_qpbap"/><path fill="url(#i80dAVc)" class="m7s_qpbap"/><path fill="url(#iFW5AQW)" class="m7s_qpbap"/><path fill="url(#inGpLze)" class="ulc7f9brx"/><path fill="url(#inGpLze)" class="ulc7f9brx"/><path fill="url(#i4VG6db)" class="e5f68hbcc"/><g filter="url(#i9MTsCc)"><path stroke="url(#icqbHne)" class="d3k_4z__i"/></g><g filter="url(#imN05Zc)"><path stroke="url(#i2lYHKb)" class="gu9i_wp-c"/></g><g filter="url(#i9QGUZc)"><path stroke="url(#ieHE6Be)" class="ng591ssdl"/></g><g filter="url(#i8PQfcy)"><path class="u32ctxstq"/></g><path fill="url(#iiXhjse)" class="o089_wbmn"/><path fill="url(#iBgKANe)" class="o089_wbmn"/><path fill="url(#iouCHre)" class="o089_wbmn"/><path fill="url(#iFoFsye)" class="o089_wbmn"/><path fill="url(#iUsWuSE)" class="ba_ozk-rb"/><path fill="url(#iUsWuSE)" class="ba_ozk-rb"/><path fill="url(#iDildac)" class="i9noy5bae"/><g filter="url(#iORbaGd)"><path stroke="url(#iH60mIc)" class="a83rzobkw"/></g><g filter="url(#iIZuLoq)"><path stroke="url(#idwdiJc)" class="sexcqbc3f"/></g><g filter="url(#iCMA49U)"><path stroke="url(#ilnQqKe)" class="va0h03b7s"/></g><defs><linearGradient id="ivlvtgd" x1="17.61" x2="25.613" y1="16.499" y2="26.023" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iAW3Pfb" x1="16.618" x2="7.226" y1="16.895" y2="27.478" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="ijHt4yd" x1="19.688" x2="16.881" y1="9.719" y2="6.636" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><linearGradient id="iC0TsBc" x1="9.394" x2="6.676" y1="16.11" y2="25.907" gradientUnits="userSpaceOnUse"><stop class="iycrgrbpr"/><stop offset="1" class="f_-ifubia"/></linearGradient><linearGradient id="i49461E" x1="7.519" x2="6.75" y1="25.345" y2="29.583" gradientUnits="userSpaceOnUse"><stop offset=".458" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="i80dAVc" x1="5.832" x2="1.597" y1="24.376" y2="24.263" gradientUnits="userSpaceOnUse"><stop offset=".362" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="inGpLze" x1="7.441" x2="6.427" y1="22.298" y2="24.464" gradientUnits="userSpaceOnUse"><stop offset=".782" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="i4VG6db" x1="9.615" x2="7.498" y1="26.891" y2="27.601" gradientUnits="userSpaceOnUse"><stop offset=".776" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="i2lYHKb" x1="9.066" x2="8.205" y1="27.485" y2="26.078" gradientUnits="userSpaceOnUse"><stop class="x8hq6m2ns"/><stop offset=".495" class="pddpbjbtb"/><stop offset="1" class="x8hq6m2ns"/></linearGradient><linearGradient id="ieHE6Be" x1="8.004" x2="9.683" y1="16.454" y2="18.896" gradientUnits="userSpaceOnUse"><stop class="o2ldtt_yw"/><stop offset="1" class="my31prb2t"/></linearGradient><linearGradient id="iiXhjse" x1="23.671" x2="22.181" y1="7.979" y2="13.349" gradientUnits="userSpaceOnUse"><stop class="iycrgrbpr"/><stop offset="1" class="f_-ifubia"/></linearGradient><linearGradient id="iBgKANe" x1="22.643" x2="22.221" y1="13.041" y2="15.364" gradientUnits="userSpaceOnUse"><stop offset=".458" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="iouCHre" x1="21.718" x2="19.398" y1="12.51" y2="12.448" gradientUnits="userSpaceOnUse"><stop offset=".362" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="iUsWuSE" x1="22.6" x2="22.045" y1="11.371" y2="12.558" gradientUnits="userSpaceOnUse"><stop offset=".782" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="iDildac" x1="23.792" x2="22.632" y1="13.888" y2="14.277" gradientUnits="userSpaceOnUse"><stop offset=".776" class="nk9rur0nr"/><stop offset="1" class="yj1mf-nxo"/></linearGradient><linearGradient id="idwdiJc" x1="23.491" x2="23.019" y1="14.214" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="x8hq6m2ns"/><stop offset=".495" class="pddpbjbtb"/><stop offset="1" class="x8hq6m2ns"/></linearGradient><linearGradient id="ilnQqKe" x1="22.909" x2="23.829" y1="8.168" y2="9.506" gradientUnits="userSpaceOnUse"><stop class="o2ldtt_yw"/><stop offset="1" class="my31prb2t"/></linearGradient><filter id="i5EJwQi" width="8.512" height="14.643" x="14.566" y="8.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation="1"/></filter><filter id="i0xy92b" width="10.174" height="10.102" x="19.62" y="6.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".75"/></filter><filter id="iwV5l9b" width="9.865" height="10.401" x="7.535" y="5.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".75"/></filter><filter id="iCqoC4b" width="5.277" height="6.494" x="4.676" y="15.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".5"/></filter><filter id="i9MTsCc" width="4.944" height="5.959" x="8.469" y="16.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".125"/></filter><filter id="imN05Zc" width="1.494" height="3.994" x="8.335" y="25.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".075"/></filter><filter id="i9QGUZc" width="2.013" height="5.059" x="6.466" y="16.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".15"/></filter><filter id="i8PQfcy" width="7.318" height="8.319" x="18.942" y="7.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".375"/></filter><filter id="iORbaGd" width="2.981" height="3.537" x="23.028" y="8.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".125"/></filter><filter id="iIZuLoq" width=".999" height="2.37" x="23" y="12.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".075"/></filter><filter id="iCMA49U" width="1.419" height="3.089" x="21.908" y="7.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6994_5077" stdDeviation=".15"/></filter><radialGradient id="iuotm1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -32.5418 55.321 0 18.8 29.33)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iTpVKIb" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 9.478 9.697)scale(26.1961 49.0678)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iisXlLe" cx="0" cy="0" r="1" gradientTransform="matrix(-21.1654 -8.2678 11.68768 -29.92024 19.859 18.152)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iXzGJJe" cx="0" cy="0" r="1" gradientTransform="rotate(90 .622 14.805)scale(19.7764)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="i2xsxVc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.621 5.824)scale(6.14843 4.1517)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="idTTIWd" cx="0" cy="0" r="1" gradientTransform="rotate(-178.3 7.55 5.87)scale(8.84998 5.97591)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iFW5AQW" cx="0" cy="0" r="1" gradientTransform="rotate(103.828 .125 10.288)scale(7.17675 19.8288)" gradientUnits="userSpaceOnUse"><stop class="g-mz8bc2f"/><stop offset="1" class="jwlwvzb-s"/></radialGradient><radialGradient id="icqbHne" cx="0" cy="0" r="1" gradientTransform="matrix(5.71875 5.35938 -4.58265 4.88994 8.129 16.782)" gradientUnits="userSpaceOnUse"><stop class="x8hq6m2ns"/><stop offset=".548" class="gpu6jublv"/><stop offset="1" class="x8hq6m2ns"/></radialGradient><radialGradient id="iFoFsye" cx="0" cy="0" r="1" gradientTransform="rotate(103.828 9.662 12.471)scale(3.93343 10.8678)" gradientUnits="userSpaceOnUse"><stop class="g-mz8bc2f"/><stop offset="1" class="jwlwvzb-s"/></radialGradient><radialGradient id="iH60mIc" cx="0" cy="0" r="1" gradientTransform="rotate(43.142 .93 33.234)scale(4.29559 3.67304)" gradientUnits="userSpaceOnUse"><stop class="x8hq6m2ns"/><stop offset=".548" class="gpu6jublv"/><stop offset="1" class="x8hq6m2ns"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sparkling-heart" /></template>
<style>
.a83rzobkw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m23.328 8.348l.402 1.347a2 2 0 0 0 1.209 1.298l.77.292");
}

.ba_ozk-rb {
  d: path("M22.286 12.441h-.237a.7.7 0 0 0-.197-.126l-1.451-.61a.274.274 0 0 1 0-.505l1.444-.608a.7.7 0 0 0 .386-.42l.648-2.003a.274.274 0 0 1 .522 0l.646 1.996c.06.19.201.343.384.42l1.452.615a.274.274 0 0 1 0 .505l-3.96.235c-.069.03.256.253.363.501");
}

.d3k_4z__i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m8.77 16.782l.966 3.24a2 2 0 0 0 1.208 1.298l2.17.822");
}

.e5f68hbcc {
  d: path("M6.435 24.251c.158.145.278.33.345.539l1.17 3.637a.5.5 0 0 0 .952 0l1.165-3.626a1.25 1.25 0 0 1 .358-.55z");
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.f_-ifubia {
  stop-color: var(--svg-color--ffa847, #FFA847);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-mz8bc2f {
  stop-color: var(--svg-color--ffff6b, #FFFF6B);
}

.gpu6jublv {
  stop-color: var(--svg-color--fff270, #FFF270);
}

.gu9i_wp-c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m8.535 28.939l1.094-3.594");
}

.i9noy5bae {
  d: path("M22.049 12.441q.132.122.19.296l.64 1.993c.082.253.44.253.522 0l.639-1.987a.7.7 0 0 1 .196-.302z");
}

.iycrgrbpr {
  stop-color: var(--svg-color--ffd542, #FFD542);
}

.jwlwvzb-s {
  stop-color: var(--svg-color--ffff6b, #FFFF6B);
  stop-opacity: 0;
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.m7s_qpbap {
  d: path("M6.768 20.11a1.25 1.25 0 0 1-.705.768l-2.635 1.107a.5.5 0 0 0 0 .922l2.647 1.113c.336.141.594.423.705.77l1.17 3.637a.5.5 0 0 0 .952 0l1.165-3.626a1.25 1.25 0 0 1 .703-.768l2.661-1.126a.5.5 0 0 0 0-.921l-2.649-1.121a1.25 1.25 0 0 1-.702-.766L8.9 16.456a.5.5 0 0 0-.951 0z");
}

.my31prb2t {
  stop-color: var(--svg-color--ff8a09, #FF8A09);
  stop-opacity: 0;
}

.ng591ssdl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m6.816 21.142l1.313-4.36");
}

.nk9rur0nr {
  stop-color: var(--svg-color--e88518, #E88518);
  stop-opacity: 0;
}

.o089_wbmn {
  d: path("M22.311 9.925a1.25 1.25 0 0 1-.705.768l-1.205.507a.274.274 0 0 0 0 .505l1.211.51c.336.14.594.422.706.769l.561 1.746c.081.253.44.253.522 0l.56-1.74a1.25 1.25 0 0 1 .702-.77l1.22-.516a.274.274 0 0 0 0-.504l-1.214-.514a1.25 1.25 0 0 1-.702-.766l-.566-1.751a.274.274 0 0 0-.522 0z");
}

.o2ldtt_yw {
  stop-color: var(--svg-color--ff8a09, #FF8A09);
  stop-opacity: 0.6;
}

.os35pryth {
  fill: var(--svg-color--a71135, #A71135);
  d: path("m8.953 20.244l-.559-3.239c-.149-.461-.484-.515-.672-.203L5.676 21.1z");
}

.p_568nbdw {
  d: path("M16.013 8.896c.892.807 2.267.573 3.02-.366c1.144-1.425 2.766-2.893 4.915-3.03c-1.825-.35-3.812.035-5.565 1.412q-.227.178-.474.366c-.485.371-1 .766-1.392 1.146c-.254.246-.698.271-.96.035l-.121-.108c.149.15.352.341.577.545");
}

.pddpbjbtb {
  stop-color: var(--svg-color--fff270, #FFF270);
  stop-opacity: 0.6;
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.r5vwmjb7p {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M16.566 12.119v6.19c0 2.714 2.87 3.621 3.744 1.05c.747-2.2 1.065-4.57.423-6.637c-.435-1.4-1.486-2.167-2.472-2.435c-1.037-.282-1.695.756-1.695 1.832");
}

.rt_h9bbqs {
  d: path("M15.084 29.551a1.73 1.73 0 0 0 1.71-.022c3.579-2.045 9.797-6.753 12.24-12.869c3.584-7.963-4.833-14.32-10.65-9.748c-.607.477-1.37 1.022-1.895 1.54c-.238.233-.657.257-.904.033c-.69-.628-1.768-1.434-2.461-1.902C8.164 3.227-.86 7.65 2.989 17.09c1.41 4.237 8.13 10.248 12.095 12.461");
}

.sexcqbc3f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m23.2 15.01l.6-1.97");
}

.u32ctxstq {
  fill: var(--svg-color--c01942, #C01942);
  d: path("M21.796 10.156a1.25 1.25 0 0 1-.654.636l-1.282.54a.274.274 0 0 0 0 .504l1.302.548c.283.119.512.337.644.613l.832 1.742c.082.254.44.254.522 0l.305-1.516a1.25 1.25 0 0 1 .738-.905l1.14-.482a.274.274 0 0 0 0-.505l-1.215-.513a1.25 1.25 0 0 1-.702-.766L22.86 8.3c-.082-.252-.14-.252-.221 0z");
}

.u67yf7bje {
  cx: 24.707px;
  cy: 11.581px;
  rx: 4.158px;
  ry: 2.861px;
}

.ulc7f9brx {
  d: path("M6.867 24.25h-.432a1.3 1.3 0 0 0-.36-.23l-2.647-1.113a.5.5 0 0 1 0-.922l2.635-1.107a1.25 1.25 0 0 0 .705-.768l1.182-3.654a.5.5 0 0 1 .951 0l1.179 3.643c.112.345.368.625.702.766l2.649 1.12a.5.5 0 0 1 0 .922l-7.224.43c-.128.054.465.46.66.914");
}

.v0kxk-buz {
  cx: 12.467px;
  cy: 11.187px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 4.158px;
  ry: 2.861px;
}

.va0h03b7s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m22.258 10.737l.72-2.39");
}

.x8hq6m2ns {
  stop-color: var(--svg-color--fff270, #FFF270);
  stop-opacity: 0;
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.yj1mf-nxo {
  stop-color: var(--svg-color--e88518, #E88518);
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yxx9jebfv {
  stop-color: var(--svg-color--b5286e, #B5286E);
}

</style>
