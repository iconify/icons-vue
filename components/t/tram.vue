<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVVX8sc)"><path fill="url(#i3vXRkc)" clip-rule="evenodd" class="b9405xhzj"/></g><path class="oljmehbaz"/><path fill="url(#iE8LK6d)" class="axalpmb8h"/><path fill="url(#iQkKKhe)" class="axalpmb8h"/><path fill="url(#inwEhCc)" class="axalpmb8h"/><path fill="url(#ivKWHJu)" class="axalpmb8h"/><path class="g_223gbnv"/><path fill="url(#i0yF8vc)" class="uk62bab5q"/><path fill="url(#iUqeQLD)" class="uk62bab5q"/><path fill="url(#i0SvdUD)" class="uk62bab5q"/><path fill="url(#iIFMMeb)" class="uk62bab5q"/><g filter="url(#iWqQ5ye)"><rect fill="url(#i0B20xU)" class="juuz60vid"/><rect fill="url(#i5lh7Be)" class="juuz60vid"/></g><g filter="url(#i2agg1d)"><path fill="url(#i2WMbuK)" class="vzdx8nb4k"/><path fill="url(#iKoi6jd)" class="vzdx8nb4k"/></g><g filter="url(#ikUxbUc)"><path fill="url(#i1gAyNe)" class="xz2v6-9tf"/></g><path fill="url(#ip3QIwc)" class="xz2v6-9tf"/><g filter="url(#i9JwJYu)"><path fill="url(#iE6vOze)" class="yb2lt--zy"/><path fill="url(#i9G396c)" class="yb2lt--zy"/></g><path fill="url(#iGI73mb)" class="uz4hsabaa"/><path fill="url(#iWVtm1c)" class="uz4hsabaa"/><rect fill="url(#i3ghLib)" class="jrqkqkb_k"/><rect fill="url(#iYnOKpe)" class="doclitb0d"/><rect fill="url(#izOechd)" class="l32rzmb6e"/><rect fill="url(#i96SzYb)" class="l32rzmb6e"/><rect fill="url(#iIqo6tP)" class="l32rzmb6e"/><g filter="url(#iZDlAFd)"><path stroke="url(#iVGzWKd)" class="yh5gapm1q"/></g><g filter="url(#iXjjrYd)"><path stroke="url(#im0jeiB)" class="tuu1gxbio"/></g><defs><linearGradient id="i3vXRkc" x1="28.367" x2="28.367" y1="20.61" y2="27.563" gradientUnits="userSpaceOnUse"><stop offset=".73" class="fwzs-hbtw"/><stop offset=".919" class="lq00qccci"/></linearGradient><linearGradient id="iE8LK6d" x1="11.943" x2="12.38" y1="5.112" y2="5.112" gradientUnits="userSpaceOnUse"><stop class="ajbyk_68x"/><stop offset="1" class="h0ipcmb6j"/></linearGradient><linearGradient id="iQkKKhe" x1="12.38" x2="12.38" y1="3.913" y2="4.221" gradientUnits="userSpaceOnUse"><stop class="ajbyk_68x"/><stop offset="1" class="h0ipcmb6j"/></linearGradient><linearGradient id="ivKWHJu" x1="14.208" x2="13.984" y1="4.018" y2="4.417" gradientUnits="userSpaceOnUse"><stop class="tbjop9b-y"/><stop offset="1" class="desjlnbba"/></linearGradient><linearGradient id="i0yF8vc" x1="17.708" x2="18.505" y1="5.112" y2="5.081" gradientUnits="userSpaceOnUse"><stop class="ajbyk_68x"/><stop offset="1" class="h0ipcmb6j"/></linearGradient><linearGradient id="iUqeQLD" x1="18.3" x2="18.3" y1="3.913" y2="4.221" gradientUnits="userSpaceOnUse"><stop class="ajbyk_68x"/><stop offset="1" class="h0ipcmb6j"/></linearGradient><linearGradient id="iIFMMeb" x1="20.129" x2="19.904" y1="4.018" y2="4.417" gradientUnits="userSpaceOnUse"><stop class="tbjop9b-y"/><stop offset="1" class="desjlnbba"/></linearGradient><linearGradient id="i5lh7Be" x1="22.924" x2="22.024" y1="3.419" y2="3.419" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="eckdnoofv"/></linearGradient><linearGradient id="i2WMbuK" x1="11.052" x2="25.427" y1="23.44" y2="23.44" gradientUnits="userSpaceOnUse"><stop class="pd055_bsk"/><stop offset="1" class="kuyh0k2ld"/></linearGradient><linearGradient id="i1gAyNe" x1="8.608" x2="20.941" y1="13.469" y2="9.254" gradientUnits="userSpaceOnUse"><stop class="s38yt1b1b"/><stop offset="1" class="um7udcb3o"/></linearGradient><linearGradient id="iE6vOze" x1="9.084" x2="22.883" y1="14.893" y2="14.893" gradientUnits="userSpaceOnUse"><stop class="z0dcxccrs"/><stop offset=".589" class="c8vnjwb9z"/><stop offset=".822" class="c8vnjwb9z"/><stop offset="1" class="kdlxxqnmu"/></linearGradient><linearGradient id="iGI73mb" x1="9.864" x2="22.364" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop class="c4w8c5b1r"/><stop offset="1" class="x54yi6bco"/></linearGradient><linearGradient id="iWVtm1c" x1="15.983" x2="15.983" y1="10.081" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="axj3fxr8h"/><stop offset="1" class="h9ug01fda"/></linearGradient><linearGradient id="izOechd" x1="15.997" x2="15.997" y1="18.8" y2="19.784" gradientUnits="userSpaceOnUse"><stop class="nps-tob4e"/><stop offset="1" class="jp54cgb_x"/></linearGradient><linearGradient id="iVGzWKd" x1="9.684" x2="9.684" y1="15.47" y2="9.268" gradientUnits="userSpaceOnUse"><stop class="uwq6jqb4x"/><stop offset="1" class="jh4-h3l2k"/></linearGradient><linearGradient id="im0jeiB" x1="10.724" x2="18.461" y1="16.588" y2="16.588" gradientUnits="userSpaceOnUse"><stop class="tvslyw6ft"/><stop offset="1" class="orztet7zv"/></linearGradient><radialGradient id="inwEhCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.11719 .43446 0 13.984 5.198)" gradientUnits="userSpaceOnUse"><stop class="kzsfz9cyl"/><stop offset="1" class="box-5xwyj"/></radialGradient><radialGradient id="i0SvdUD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.11719 .43446 0 19.904 5.198)" gradientUnits="userSpaceOnUse"><stop class="kzsfz9cyl"/><stop offset="1" class="box-5xwyj"/></radialGradient><radialGradient id="i0B20xU" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35142 -13.6262 0 19.49 2.753)" gradientUnits="userSpaceOnUse"><stop class="ljeo-0znr"/><stop offset="1" class="d6_h-6gdy"/></radialGradient><radialGradient id="iKoi6jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76028 -.9956 2.44315 -1.8657 23.784 22.922)" gradientUnits="userSpaceOnUse"><stop class="j53hhrili"/><stop offset="1" class="n0080-mnj"/></radialGradient><radialGradient id="ip3QIwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.04524 18.2752 0 16 18.585)" gradientUnits="userSpaceOnUse"><stop class="qrskzvbvf"/><stop offset="1" class="ryrb7xb0a"/></radialGradient><radialGradient id="i9G396c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.17222 8.76128 0 17.702 16.894)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="c4cjyxbgu"/><stop offset="1" class="bn5uglbli"/></radialGradient><radialGradient id="i3ghLib" cx="0" cy="0" r="1" gradientTransform="matrix(3.24921 0 0 2.01281 9.42 20.603)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="magi6ybke"/><stop offset="1" class="cy2l0tb1q"/><stop offset="1" class="tgadrebkj"/></radialGradient><radialGradient id="iYnOKpe" cx="0" cy="0" r="1" gradientTransform="matrix(3.24921 0 0 2.01281 19.262 20.603)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="magi6ybke"/><stop offset="1" class="cy2l0tb1q"/><stop offset="1" class="tgadrebkj"/></radialGradient><radialGradient id="i96SzYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.35423 0 0 1.16216 15.703 19.417)" gradientUnits="userSpaceOnUse"><stop offset=".762" class="ddj-mzn3e"/><stop offset="1" class="fvy6zlpjg"/></radialGradient><radialGradient id="iIqo6tP" cx="0" cy="0" r="1" gradientTransform="matrix(-4.3779 0 0 -2.62847 18.299 19.502)" gradientUnits="userSpaceOnUse"><stop offset=".904" class="fmdhzwb_y"/><stop offset="1" class="ykg-r_b2g"/></radialGradient><filter id="iVVX8sc" width="17.95" height="6.575" x="7.009" y="21.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9540" result="effect2_innerShadow_18_9540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.12549 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_9540" result="effect3_innerShadow_18_9540"/></filter><filter id="iWqQ5ye" width="14.481" height="2.129" x="9.043" y="1.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.541176 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9540"/></filter><filter id="i2agg1d" width="18.737" height="12.711" x="7.132" y="11.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.227451 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9540"/></filter><filter id="ikUxbUc" width="18.987" height="12.98" x="6.382" y="5.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".355"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.839216 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9540" result="effect2_innerShadow_18_9540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.580392 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_9540" result="effect3_innerShadow_18_9540"/></filter><filter id="i9JwJYu" width="14.549" height="6.424" x="8.334" y="10.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.65098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9540"/></filter><filter id="iZDlAFd" width="1.25" height="5.547" x="9.091" y="10.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9540" stdDeviation=".125"/></filter><filter id="iXjjrYd" width="10.688" height=".75" x="9.677" y="15.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9540" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tram" /></template>
<style>
.ajbyk_68x {
  stop-color: var(--svg-color--888789, #888789);
}

.axalpmb8h {
  d: path("M12.046 3.913h1.938v2.006h-1.938z");
}

.axj3fxr8h {
  stop-color: var(--svg-color--3e2257, #3E2257);
}

.b9405xhzj {
  fill-rule: evenodd;
  d: path("M9.803 23.175c-.874 1.332-1.926 2.934-2.025 3.106l-.075.126c-.19.31-.438.715-.19 1.142c.282.486.946.493 1.082.493h14.966c.322 0 .6-.097.852-.427c.253-.331.158-.769-.157-1.163c-.219-.273-1.315-1.977-2.188-3.333c-.412-.64-.774-1.203-.97-1.501H10.824zm1.024 1.479l.308-.512c.078-.126.438-.413.895-.413l7.977.07c.399 0 .598.09.783.363c.148.218.24.336.363.492zm-1.153 1.742c.058-.078.222-.317.308-.457c.162-.265.45-.356.908-.356h10.362c.39 0 .565.167.706.38c.078.116.201.323.273.433z");
}

.bn5uglbli {
  stop-color: var(--svg-color--56e8ff, #56E8FF);
  stop-opacity: 0;
}

.box-5xwyj {
  stop-color: var(--svg-color--e2e0e3, #E2E0E3);
  stop-opacity: 0;
}

.c4cjyxbgu {
  stop-color: var(--svg-color--56e8ff, #56E8FF);
}

.c4w8c5b1r {
  stop-color: var(--svg-color--4b3e59, #4B3E59);
}

.c8vnjwb9z {
  stop-color: var(--svg-color--5bdeff, #5BDEFF);
}

.cy2l0tb1q {
  stop-color: var(--svg-color--fb730d, #FB730D);
}

.d6_h-6gdy {
  stop-color: var(--svg-color--bdb8c3, #BDB8C3);
}

.ddj-mzn3e {
  stop-color: var(--svg-color--a08eb3, #A08EB3);
  stop-opacity: 0;
}

.desjlnbba {
  stop-color: var(--svg-color--8f8c92, #8F8C92);
  stop-opacity: 0;
}

.doclitb0d {
  width: 3.961px;
  height: 1.953px;
  x: 18.922px;
  y: 18.925px;
  rx: 0.977px;
}

.eckdnoofv {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
  stop-opacity: 0;
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.fmdhzwb_y {
  stop-color: var(--svg-color--dcd0e8, #DCD0E8);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvy6zlpjg {
  stop-color: var(--svg-color--a08eb3, #A08EB3);
}

.fwzs-hbtw {
  stop-color: var(--svg-color--0c0e1c, #0C0E1C);
}

.g_223gbnv {
  fill: var(--svg-color--d2d0d6, #D2D0D6);
  d: path("M17.966 3.913h1.938v2.006h-1.938z");
}

.h0ipcmb6j {
  stop-color: var(--svg-color--888789, #888789);
  stop-opacity: 0;
}

.h9ug01fda {
  stop-color: var(--svg-color--3e2257, #3E2257);
  stop-opacity: 0;
}

.j53hhrili {
  stop-color: var(--svg-color--d6356c, #D6356C);
}

.jh4-h3l2k {
  stop-color: var(--svg-color--63d4ff, #63D4FF);
  stop-opacity: 0;
}

.jp54cgb_x {
  stop-color: var(--svg-color--decfec, #DECFEC);
}

.jrqkqkb_k {
  width: 3.961px;
  height: 1.953px;
  x: 9.079px;
  y: 18.925px;
  rx: 0.977px;
}

.juuz60vid {
  width: 13.881px;
  height: 1.979px;
  x: 9.043px;
  y: 2.125px;
  rx: 0.99px;
}

.kdlxxqnmu {
  stop-color: var(--svg-color--4fb8ff, #4FB8FF);
}

.kuyh0k2ld {
  stop-color: var(--svg-color--f92f56, #F92F56);
}

.kzsfz9cyl {
  stop-color: var(--svg-color--e2e0e3, #E2E0E3);
}

.l32rzmb6e {
  width: 3.938px;
  height: 0.984px;
  x: 14.028px;
  y: 18.925px;
  rx: 0.492px;
}

.ljeo-0znr {
  stop-color: var(--svg-color--e2dde8, #E2DDE8);
}

.lq00qccci {
  stop-color: var(--svg-color--56218e, #56218E);
}

.magi6ybke {
  stop-color: var(--svg-color--ffb432, #FFB432);
}

.n0080-mnj {
  stop-color: var(--svg-color--d6356c, #D6356C);
  stop-opacity: 0;
}

.nps-tob4e {
  stop-color: var(--svg-color--b68fdb, #B68FDB);
}

.oljmehbaz {
  fill: var(--svg-color--c8c6cb, #C8C6CB);
  d: path("M12.046 3.913h1.938v2.006h-1.938z");
}

.orztet7zv {
  stop-color: var(--svg-color--57e5ff, #57E5FF);
}

.pd055_bsk {
  stop-color: var(--svg-color--df2e96, #DF2E96);
}

.qrskzvbvf {
  stop-color: var(--svg-color--e8d2ff, #E8D2FF);
}

.ryrb7xb0a {
  stop-color: var(--svg-color--e8d2ff, #E8D2FF);
  stop-opacity: 0;
}

.s38yt1b1b {
  stop-color: var(--svg-color--d9c3f1, #D9C3F1);
}

.tbjop9b-y {
  stop-color: var(--svg-color--8f8c92, #8F8C92);
}

.tgadrebkj {
  stop-color: var(--svg-color--ff7324, #FF7324);
}

.tuu1gxbio {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.052 15.503h9.937");
}

.tvslyw6ft {
  stop-color: var(--svg-color--62d3ff, #62D3FF);
  stop-opacity: 0.5;
}

.uk62bab5q {
  d: path("M17.966 3.913h1.938v2.006h-1.938z");
}

.um7udcb3o {
  stop-color: var(--svg-color--ecddfc, #ECDDFC);
}

.uwq6jqb4x {
  stop-color: var(--svg-color--62d3ff, #62D3FF);
}

.uz4hsabaa {
  d: path("M22.883 10h-13.8V7.94a.9.9 0 0 1 .9-.9h12a.9.9 0 0 1 .9.9z");
}

.vzdx8nb4k {
  d: path("M7.132 11.12h17.736v8.71a4 4 0 0 1-4 4h-9.736a4 4 0 0 1-4-4z");
}

.x54yi6bco {
  stop-color: var(--svg-color--5c4575, #5C4575);
}

.xz2v6-9tf {
  d: path("M7.132 7.128a2 2 0 0 1 2-2h13.736a2 2 0 0 1 2 2v7.93a2.9 2.9 0 0 1-2.9 2.9H10.032a2.9 2.9 0 0 1-2.9-2.9z");
}

.yb2lt--zy {
  d: path("M9.084 10h13.799v4.924a1 1 0 0 1-1 1h-11.8a1 1 0 0 1-1-1z");
}

.yh5gapm1q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.466 10.673v4.297a.5.5 0 0 0 .5.5");
}

.ykg-r_b2g {
  stop-color: var(--svg-color--dcd0e8, #DCD0E8);
}

.z0dcxccrs {
  stop-color: var(--svg-color--47bcff, #47BCFF);
}

</style>
