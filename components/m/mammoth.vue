<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igUAzbh)" class="xih7kvzsj"/><path fill="url(#iiPmmkH)" class="xih7kvzsj"/><path class="vggzlacvm"/><path fill="url(#iMFciNz)" class="bm6sx4u3p"/><path class="xlbrkac0j"/><path fill="url(#iHPWcce)" class="jan_myj8k"/><path fill="url(#i9RcBLb)" class="jan_myj8k"/><path fill="url(#iMlehJe)" class="jan_myj8k"/><path fill="url(#iVxms0a)" class="jan_myj8k"/><path fill="url(#iLT4Tge)" class="jan_myj8k"/><path fill="url(#iaHil3b)" class="jan_myj8k"/><path fill="url(#iJExfTb)" class="jan_myj8k"/><path fill="url(#iN9gMuc)" class="jan_myj8k"/><path fill="url(#irKEuLd)" class="jan_myj8k"/><path fill="url(#iTunXkc)" class="jan_myj8k"/><path fill="url(#iHXI4fc)" class="jan_myj8k"/><path fill="url(#isrGmSd)" class="jan_myj8k"/><path fill="url(#imLAkMb)" class="jan_myj8k"/><path fill="url(#ieyjKIe)" class="jan_myj8k"/><g filter="url(#iOxuenb)"><ellipse fill="url(#iBuCA3c)" transform="rotate(-38.018 16.807 6.264)" class="hzf4ybc7l"/></g><g filter="url(#idvAKSc)"><ellipse fill="url(#iX1cHKc)" transform="rotate(-39.505 25.447 11.493)" class="fgpwxfm9s"/></g><g filter="url(#i4NEFUc)"><path class="jvlntobpb"/></g><path fill="url(#ilRLgnb)" class="szmp5p0nu"/><path fill="url(#ik9tFZb)" class="szmp5p0nu"/><path fill="url(#iXqaf3t)" class="szmp5p0nu"/><path fill="url(#i50J8we)" class="szmp5p0nu"/><path fill="url(#i7ar0Td)" class="szmp5p0nu"/><path fill="url(#ivi6RYb)" class="szmp5p0nu"/><path fill="url(#iTZOd1c)" class="szmp5p0nu"/><g filter="url(#iXdVW3c)"><path class="jqbd7nbit"/></g><path fill="url(#i4ZiNtU)" class="bit02gbus"/><path fill="url(#ilMdtNb)" class="bit02gbus"/><path fill="url(#iXEOKOj)" class="bit02gbus"/><path class="mpz0eibvt"/><path fill="url(#iWaOVDk)" class="z0a2vw2ri"/><g filter="url(#igbuGmc)"><path stroke="url(#ikDL9Fc)" class="b2ndfobzn"/></g><g filter="url(#izJjC5d)"><path class="jsj-00j5m"/></g><path fill="url(#iAdupMc)" class="b517rwb_z"/><path fill="url(#iZyeVxb)" class="b517rwb_z"/><path fill="url(#iPBMtfq)" class="b517rwb_z"/><path fill="url(#ihuECZb)" class="b517rwb_z"/><path fill="url(#iBC8Isc)" class="b517rwb_z"/><g filter="url(#iZaLqTd)"><path stroke="url(#iZcjPAc)" class="ektjlznkm"/></g><g filter="url(#ipnrTyd)"><path stroke="url(#iZsJETd)" class="nnn24vl0u"/></g><g filter="url(#iDsXYac)"><path class="bj5m_0b5e"/></g><g filter="url(#i6Ib4He)"><path class="vx187fbdj"/></g><defs><radialGradient id="igUAzbh" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 4.625 -3.29212 .48937 18.757 25.997)" gradientUnits="userSpaceOnUse"><stop class="yaarqvbns"/><stop offset="1" class="cvhusmb_g"/></radialGradient><radialGradient id="i9RcBLb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.255 -4.5 3.2279 -3.05216 21.226 23.372)" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset="1" class="gd70hy95j"/></radialGradient><radialGradient id="iMlehJe" cx="0" cy="0" r="1" gradientTransform="rotate(-50.194 26.521 .169)scale(4.39327 3.01686)" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset="1" class="gd70hy95j"/></radialGradient><radialGradient id="iVxms0a" cx="0" cy="0" r="1" gradientTransform="rotate(-75.822 20.79 9.06)scale(3.06202 4.53228)" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset="1" class="gd70hy95j"/></radialGradient><radialGradient id="iLT4Tge" cx="0" cy="0" r="1" gradientTransform="rotate(-129.139 16.417 7.04)scale(6.88964 5.49826)" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset=".648" class="gd70hy95j"/></radialGradient><radialGradient id="iJExfTb" cx="0" cy="0" r="1" gradientTransform="matrix(2.68746 -4.43753 3.34006 2.02281 10.257 21.592)" gradientUnits="userSpaceOnUse"><stop class="hdglo8bwe"/><stop offset="1" class="fbb8-db9k"/></radialGradient><radialGradient id="irKEuLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 6.375 -4.32445 1.2719 11.6 3.373)" gradientUnits="userSpaceOnUse"><stop class="wo3h04isz"/><stop offset="1" class="v6jy_zr2j"/></radialGradient><radialGradient id="iTunXkc" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 .6875 -.2052 1.3804 3.038 7.247)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="wo3h04isz"/><stop offset="1" class="v6jy_zr2j"/></radialGradient><radialGradient id="iHXI4fc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5625 -1.15626 1.6486 -3.6536 7.6 18.841)" gradientUnits="userSpaceOnUse"><stop class="r77sw3wua"/><stop offset=".714" class="yfr4ercrx"/></radialGradient><radialGradient id="isrGmSd" cx="0" cy="0" r="1" gradientTransform="rotate(122.681 -3.157 11.91)scale(1.96776 2.80563)" gradientUnits="userSpaceOnUse"><stop class="r77sw3wua"/><stop offset="1" class="yfr4ercrx"/></radialGradient><radialGradient id="imLAkMb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.158 83.049 -53)scale(5.25966 7.10188)" gradientUnits="userSpaceOnUse"><stop class="mzow3tb8w"/><stop offset="1" class="mmhlhtb7i"/></radialGradient><radialGradient id="ieyjKIe" cx="0" cy="0" r="1" gradientTransform="matrix(2.14062 2.125 -.88747 .894 7.366 3.31)" gradientUnits="userSpaceOnUse"><stop class="b0ki80k7n"/><stop offset="1" class="lmo249b4l"/></radialGradient><radialGradient id="iBuCA3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31184 4.93593 -3.4668 -1.62374 18.788 5.73)" gradientUnits="userSpaceOnUse"><stop class="mhzmsi1xs"/><stop offset="1" class="yqe4cybrl"/></radialGradient><radialGradient id="iX1cHKc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.87696 7.86931 -4.64049 -1.69652 27.913 10.642)" gradientUnits="userSpaceOnUse"><stop class="mhzmsi1xs"/><stop offset="1" class="yqe4cybrl"/></radialGradient><radialGradient id="iXqaf3t" cx="0" cy="0" r="1" gradientTransform="matrix(5.96873 6.43752 -10.67975 9.90203 10.07 7.935)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ni-urdb6s"/><stop offset=".972" class="dszmkrbzp"/></radialGradient><radialGradient id="i50J8we" cx="0" cy="0" r="1" gradientTransform="matrix(.03123 10.34375 -8.36753 .02527 12.226 10.03)" gradientUnits="userSpaceOnUse"><stop class="awzhroj9b"/><stop offset="1" class="ykwkirnsy"/></radialGradient><radialGradient id="iXEOKOj" cx="0" cy="0" r="1" gradientTransform="rotate(-109.909 9.124 3.45)scale(1.13281 1.12122)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iZyeVxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.025 .774 9.229)scale(1.92079 2.93051)" gradientUnits="userSpaceOnUse"><stop class="cl_4h5u-b"/><stop offset="1" class="ocqjkhbst"/></radialGradient><radialGradient id="ihuECZb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.25004 6.87496 -5.95571 -5.41434 9.445 13.748)" gradientUnits="userSpaceOnUse"><stop offset=".845" class="gpe3s-aca"/><stop offset="1" class="n6mr6cbke"/></radialGradient><radialGradient id="iBC8Isc" cx="0" cy="0" r="1" gradientTransform="matrix(11.31247 2.37505 -1.33338 6.35094 -1.024 16.373)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="cjnss_8bd"/><stop offset="1" class="tyg_16b3t"/></radialGradient><linearGradient id="iiPmmkH" x1="20.172" x2="20.172" y1="29.591" y2="27.06" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset=".69" class="gd70hy95j"/></linearGradient><linearGradient id="iMFciNz" x1="25.07" x2="25.07" y1="29.435" y2="27.841" gradientUnits="userSpaceOnUse"><stop class="x5f-0e2vr"/><stop offset="1" class="pkd6dqbqq"/></linearGradient><linearGradient id="iHPWcce" x1="1.226" x2="15.976" y1="21.747" y2="21.747" gradientUnits="userSpaceOnUse"><stop class="kca4kgbav"/><stop offset="1" class="v45v2_byx"/></linearGradient><linearGradient id="iaHil3b" x1="25.788" x2="25.788" y1="29.685" y2="26.06" gradientUnits="userSpaceOnUse"><stop class="k5f0td_zb"/><stop offset=".69" class="gd70hy95j"/></linearGradient><linearGradient id="iN9gMuc" x1="2.851" x2="7.226" y1="20.435" y2="20.435" gradientUnits="userSpaceOnUse"><stop class="wo3h04isz"/><stop offset="1" class="v6jy_zr2j"/></linearGradient><linearGradient id="ilRLgnb" x1="14.976" x2="13.351" y1="6.06" y2="13.279" gradientUnits="userSpaceOnUse"><stop class="m_tl88bid"/><stop offset="1" class="t5bfaqbul"/></linearGradient><linearGradient id="ik9tFZb" x1="14.476" x2="14.476" y1="16.372" y2="15.044" gradientUnits="userSpaceOnUse"><stop class="dszmkrbzp"/><stop offset="1" class="ni-urdb6s"/></linearGradient><linearGradient id="i7ar0Td" x1="15.195" x2="15.195" y1="4.56" y2="6.997" gradientUnits="userSpaceOnUse"><stop offset=".228" class="u11ty672l"/><stop offset="1" class="jpt9hkb7u"/></linearGradient><linearGradient id="ivi6RYb" x1="9.851" x2="12.788" y1="7.997" y2="7.997" gradientUnits="userSpaceOnUse"><stop offset=".228" class="u11ty672l"/><stop offset="1" class="jpt9hkb7u"/></linearGradient><linearGradient id="iTZOd1c" x1="17.507" x2="16.538" y1="13.31" y2="12.185" gradientUnits="userSpaceOnUse"><stop class="u11ty672l"/><stop offset="1" class="jpt9hkb7u"/></linearGradient><linearGradient id="i4ZiNtU" x1="9.292" x2="8.713" y1="13.087" y2="13.087" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="ilMdtNb" x1="9.449" x2="9.449" y1="14.092" y2="13.175" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iWaOVDk" x1="9.066" x2="9.066" y1="17.372" y2="16.435" gradientUnits="userSpaceOnUse"><stop class="qgzz0bbou"/><stop offset=".507" class="dxy77z8_t"/></linearGradient><linearGradient id="ikDL9Fc" x1="10.356" x2="9.445" y1="14.998" y2="16.372" gradientUnits="userSpaceOnUse"><stop class="hjhpflbkg"/><stop offset="1" class="nawjh63pj"/></linearGradient><linearGradient id="iAdupMc" x1="3.288" x2="10.059" y1="17.267" y2="17.267" gradientUnits="userSpaceOnUse"><stop class="lhirbubip"/><stop offset="1" class="ca-0evbtq"/></linearGradient><linearGradient id="iPBMtfq" x1="1.82" x2="3.195" y1="21.36" y2="21.36" gradientUnits="userSpaceOnUse"><stop class="n6mr6cbke"/><stop offset=".615" class="gpe3s-aca"/></linearGradient><linearGradient id="iZcjPAc" x1="17.882" x2="14.742" y1="10.091" y2="6.269" gradientUnits="userSpaceOnUse"><stop class="o80xwse_o"/><stop offset=".475" class="nl61zr1vh"/><stop offset="1" class="o80xwse_o"/></linearGradient><linearGradient id="iZsJETd" x1="8.27" x2="5.522" y1="20.348" y2="13.784" gradientUnits="userSpaceOnUse"><stop class="wa153vb5v"/><stop offset="1" class="st4ecl0sr"/></linearGradient><filter id="iOxuenb" width="7.347" height="7.719" x="13.133" y="2.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".75"/></filter><filter id="idvAKSc" width="9.395" height="10.089" x="20.75" y="6.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".75"/></filter><filter id="i4NEFUc" width="7.587" height="11.275" x="10.755" y="5.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".4"/></filter><filter id="iXdVW3c" width="1.949" height="2.855" x="7.734" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".25"/></filter><filter id="igbuGmc" width="3.78" height="3.84" x="7.176" y="14.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".15"/></filter><filter id="izJjC5d" width="3.813" height="5.219" x="4.963" y="20.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".4"/></filter><filter id="iZaLqTd" width="4.171" height="4.213" x="13.899" y="6.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".2"/></filter><filter id="ipnrTyd" width="6.342" height="7.644" x="2.084" y="13.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".25"/></filter><filter id="iDsXYac" width="1.876" height="2.958" x="8.466" y="14.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".3"/></filter><filter id="i6Ib4He" width="4.25" height="9.156" x="16.866" y="20.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3508" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mammoth" /></template>
<style>
.awzhroj9b {
  stop-color: var(--svg-color--6c4340, #6C4340);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b0ki80k7n {
  stop-color: var(--svg-color--89675e, #89675E);
}

.b2ndfobzn {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.506 17.029V15.97c0-.793-.647-1.44-1.44-1.44s-1.44.647-1.44 1.44v1.05c0 .253.197.45.45.45h1.97a.46.46 0 0 0 .46-.441Z");
}

.b517rwb_z {
  d: path("M8.056 17.32c0 1.13-.92 2.04-2.04 2.04c-1.12.01-2.04-.91-2.04-2.04v-.86c0-.86-.2-1.7-.58-2.46l-.25-.49a.61.61 0 0 0-.55-.34c-.34 0-.62.27-.62.61v3.54c0 2.23 1.81 4.04 4.04 4.04s4.04-1.81 4.04-4.04z");
}

.bit02gbus {
  d: path("M8.792 14.064c-.28 0-.5-.22-.5-.5v-.954c0-.28.22-.5.5-.5s.5.22.5.5v.954c0 .28-.22.5-.5.5");
}

.bj5m_0b5e {
  fill: var(--svg-color--8e6a65, #8E6A65);
  d: path("M9.066 15.519a.338.338 0 1 1 .676 0v1.42h-.676z");
}

.bm6sx4u3p {
  d: path("m21.976 22.06l.51.25a2.69 2.69 0 0 1 1.49 2.42v3.39c0 .52.42.94.94.94h3.12c.52 0 .94-.42.94-.94v-6.06z");
}

.ca-0evbtq {
  stop-color: var(--svg-color--f5a86e, #F5A86E);
}

.cjnss_8bd {
  stop-color: var(--svg-color--e3925e, #E3925E);
  stop-opacity: 0;
}

.cl_4h5u-b {
  stop-color: var(--svg-color--ffea9e, #FFEA9E);
}

.cvhusmb_g {
  stop-color: var(--svg-color--4b1e24, #4B1E24);
}

.dszmkrbzp {
  stop-color: var(--svg-color--5a3046, #5A3046);
}

.dxy77z8_t {
  stop-color: var(--svg-color--763f4e, #763F4E);
  stop-opacity: 0.079;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.ektjlznkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.399 6.753c.84.083 2.92.666 3.17 3.213");
}

.fbb8-db9k {
  stop-color: var(--svg-color--60383b, #60383B);
  stop-opacity: 0;
}

.fgpwxfm9s {
  cx: 25.447px;
  cy: 11.493px;
  rx: 2.294px;
  ry: 4.185px;
}

.ft5dv1b6b {
  fill: none;
}

.gd70hy95j {
  stop-color: var(--svg-color--6a315a, #6A315A);
  stop-opacity: 0;
}

.gpe3s-aca {
  stop-color: var(--svg-color--ba8961, #BA8961);
  stop-opacity: 0;
}

.hdglo8bwe {
  stop-color: var(--svg-color--60383b, #60383B);
}

.hjhpflbkg {
  stop-color: var(--svg-color--88635e, #88635E);
}

.hzf4ybc7l {
  cx: 16.807px;
  cy: 6.264px;
  rx: 1.844px;
  ry: 2.625px;
}

.jan_myj8k {
  d: path("M21.226 6.06c-.83 0-1.59-.42-2.07-1.09a4.49 4.49 0 0 0-3.68-1.91c-1.52 0-2.86.75-3.68 1.91l-.01.01c-.45.63-1.31.8-1.97.41l-2.9-1.67a.383.383 0 0 0-.58.31c-.04.67.18 1.32.6 1.82c.07.08.01.21-.1.21h-2.23c-.19 0-.35.16-.35.35c0 .16.04.31.13.44c.25.4.6.71 1 .92c-.87.94-1.41 2.21-1.41 3.6v11.69c0 1.66 1.34 3 3 3h.5c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5h-.17c-.18 0-.33-.15-.33-.33v-3.29c0-.21.17-.38.38-.38h1.37c.77 0 1.52.3 2.07.85l.29.28c.57.56.89 1.32.89 2.11c0 .49-.15.98-.42 1.39l-2.28 3.43c-.56.83.04 1.94 1.04 1.94h2.39c.79 0 1.51-.42 1.9-1.1l3.1-5.43c.17-.29.48-.47.81-.47h3.89c.37 0 .74.09 1.07.25a2.69 2.69 0 0 1 1.49 2.42v3.39c0 .52.42.94.94.94h3.12c.52 0 .94-.42.94-.94V14.81c.01-4.83-3.91-8.75-8.74-8.75");
}

.jpt9hkb7u {
  stop-color: var(--svg-color--5a3535, #5A3535);
  stop-opacity: 0;
}

.jqbd7nbit {
  fill: var(--svg-color--6b3b3d, #6B3B3D);
  d: path("M8.708 14.098a.47.47 0 0 1-.474-.475v-.906a.47.47 0 0 1 .474-.475a.47.47 0 0 1 .475.475v.906a.47.47 0 0 1-.475.475");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jsj-00j5m {
  stroke: var(--svg-color--9e746f, #9E746F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.963 21.076v1.718a1.5 1.5 0 0 0 1.5 1.5h.313");
}

.jvlntobpb {
  fill: var(--svg-color--60332f, #60332F);
  d: path("M17.535 9.832a3.765 3.765 0 0 0-3.949-3.439l-1.397.074a.67.67 0 0 0-.633.705l.426 8.015c.043.805 1.026 1.17 1.588.596l2.432-2.211a4.76 4.76 0 0 0 1.533-3.74");
}

.k5f0td_zb {
  stop-color: var(--svg-color--873d72, #873D72);
}

.kca4kgbav {
  stop-color: var(--svg-color--704440, #704440);
}

.lhirbubip {
  stop-color: var(--svg-color--e1a776, #E1A776);
}

.lmo249b4l {
  stop-color: var(--svg-color--89675e, #89675E);
  stop-opacity: 0;
}

.m_tl88bid {
  stop-color: var(--svg-color--704b4a, #704B4A);
}

.mhzmsi1xs {
  stop-color: var(--svg-color--996f67, #996F67);
}

.mmhlhtb7i {
  stop-color: var(--svg-color--693944, #693944);
  stop-opacity: 0;
}

.mpz0eibvt {
  fill: var(--svg-color--754940, #754940);
  d: path("M10.046 17.32h-1.97c-.17 0-.3-.13-.3-.3v-1.05c0-.71.58-1.29 1.29-1.29s1.29.58 1.29 1.29v1.05a.31.31 0 0 1-.31.3");
}

.mzow3tb8w {
  stop-color: var(--svg-color--693944, #693944);
}

.n6mr6cbke {
  stop-color: var(--svg-color--ba8961, #BA8961);
}

.nawjh63pj {
  stop-color: var(--svg-color--88635e, #88635E);
  stop-opacity: 0;
}

.ni-urdb6s {
  stop-color: var(--svg-color--5a3046, #5A3046);
  stop-opacity: 0;
}

.nl61zr1vh {
  stop-color: var(--svg-color--816661, #816661);
}

.nnn24vl0u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M2.734 13.716c.18.328.682 1.547.682 2.719c0 1.281.016 2.031.329 2.5a2.51 2.51 0 0 0 2.14 1.125c.925 0 1.646-.542 1.89-.812");
}

.o80xwse_o {
  stop-color: var(--svg-color--816661, #816661);
  stop-opacity: 0;
}

.ocqjkhbst {
  stop-color: var(--svg-color--ffea9e, #FFEA9E);
  stop-opacity: 0;
}

.pkd6dqbqq {
  stop-color: var(--svg-color--723365, #723365);
  stop-opacity: 0;
}

.qgzz0bbou {
  stop-color: var(--svg-color--763f4e, #763F4E);
}

.r77sw3wua {
  stop-color: var(--svg-color--562727, #562727);
}

.st4ecl0sr {
  stop-color: var(--svg-color--fff0bb, #FFF0BB);
}

.szmp5p0nu {
  d: path("M17.976 9.81a3.875 3.875 0 0 0-3.87-3.75h-1.44c-.38 0-.69.31-.69.69v8.26c0 .83.99 1.26 1.6.7l2.62-2.14a4.9 4.9 0 0 0 1.78-3.76");
}

.t5bfaqbul {
  stop-color: var(--svg-color--684345, #684345);
}

.tyg_16b3t {
  stop-color: var(--svg-color--e3925e, #E3925E);
}

.u11ty672l {
  stop-color: var(--svg-color--5a3535, #5A3535);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.v45v2_byx {
  stop-color: var(--svg-color--704440, #704440);
  stop-opacity: 0;
}

.v6jy_zr2j {
  stop-color: var(--svg-color--664644, #664644);
  stop-opacity: 0;
}

.vggzlacvm {
  fill: var(--svg-color--4f272f, #4F272F);
  d: path("m21.976 22.06l.51.25a2.69 2.69 0 0 1 1.49 2.42v3.39c0 .52.42.94.94.94h3.12c.52 0 .94-.42.94-.94v-6.06z");
}

.vx187fbdj {
  fill: var(--svg-color--765053, #765053);
  d: path("m18.367 22.373l1.25.812v5.344h-1.25z");
}

.wa153vb5v {
  stop-color: var(--svg-color--fff0bb, #FFF0BB);
  stop-opacity: 0;
}

.wo3h04isz {
  stop-color: var(--svg-color--664644, #664644);
}

.x5f-0e2vr {
  stop-color: var(--svg-color--723365, #723365);
}

.xih7kvzsj {
  d: path("M20.976 22.06h-5v6.06c0 .52.42.94.94.94h3.12c.52 0 .94-.42.94-.94z");
}

.xlbrkac0j {
  fill: var(--svg-color--825452, #825452);
  d: path("M21.226 6.06c-.83 0-1.59-.42-2.07-1.09a4.49 4.49 0 0 0-3.68-1.91c-1.52 0-2.86.75-3.68 1.91l-.01.01c-.45.63-1.31.8-1.97.41l-2.9-1.67a.383.383 0 0 0-.58.31c-.04.67.18 1.32.6 1.82c.07.08.01.21-.1.21h-2.23c-.19 0-.35.16-.35.35c0 .16.04.31.13.44c.25.4.6.71 1 .92c-.87.94-1.41 2.21-1.41 3.6v11.69c0 1.66 1.34 3 3 3h.5c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5h-.17c-.18 0-.33-.15-.33-.33v-3.29c0-.21.17-.38.38-.38h1.37c.77 0 1.52.3 2.07.85l.29.28c.57.56.89 1.32.89 2.11c0 .49-.15.98-.42 1.39l-2.28 3.43c-.56.83.04 1.94 1.04 1.94h2.39c.79 0 1.51-.42 1.9-1.1l3.1-5.43c.17-.29.48-.47.81-.47h3.89c.37 0 .74.09 1.07.25a2.69 2.69 0 0 1 1.49 2.42v3.39c0 .52.42.94.94.94h3.12c.52 0 .94-.42.94-.94V14.81c.01-4.83-3.91-8.75-8.74-8.75");
}

.yaarqvbns {
  stop-color: var(--svg-color--693a40, #693A40);
}

.yfr4ercrx {
  stop-color: var(--svg-color--562727, #562727);
  stop-opacity: 0;
}

.ykwkirnsy {
  stop-color: var(--svg-color--6c4340, #6C4340);
  stop-opacity: 0;
}

.yqe4cybrl {
  stop-color: var(--svg-color--986e65, #986E65);
  stop-opacity: 0;
}

.z0a2vw2ri {
  d: path("M10.046 17.32h-1.97c-.17 0-.3-.13-.3-.3v-1.05c0-.71.58-1.29 1.29-1.29s1.29.58 1.29 1.29v1.05a.31.31 0 0 1-.31.3");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
