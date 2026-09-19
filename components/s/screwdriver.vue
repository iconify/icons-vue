<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwOs2jb)"><path fill="url(#iWgdxCm)" class="ilqy-bb8f"/><path fill="url(#ikw7fjg)" class="ilqy-bb8f"/><path fill="url(#ilsZecd)" class="ilqy-bb8f"/></g><g filter="url(#iTmkd4e)"><path class="dt_dalb1v"/></g><path fill="url(#i5fzuCd)" class="cjm18vb6q"/><path fill="url(#iwmNxge)" class="cjm18vb6q"/><path fill="url(#isaHQ1c)" class="cjm18vb6q"/><path fill="url(#ifG386D)" class="cjm18vb6q"/><g filter="url(#ictg3yb)"><path fill="url(#i0nknHc)" clip-rule="evenodd" class="il7k-pbek"/><path stroke="url(#ittHtAd)" class="os53xgbig"/></g><g filter="url(#iugPvhb)"><rect fill="url(#i1Uy1gb)" transform="rotate(-45 19.893 17.76)" class="tdlmmb8ac"/></g><g filter="url(#igU6hLc)"><rect fill="url(#iHSFWRf)" transform="rotate(-45 16 20.584)" class="bgtzsu8xr"/></g><g filter="url(#iBLiCUd)"><rect fill="url(#iWYlCKe)" transform="rotate(-45 16.64 20.604)" class="a54lbcbfa"/></g><g filter="url(#i6KxcZb)"><rect fill="url(#ig1hnsd)" transform="scale(-1 1)rotate(45 -33.611 -10.33)" class="r2kmcbbnl"/></g><rect fill="url(#i3xlEoL)" transform="rotate(-45 11.632 18.66)" class="o4yzuw49p"/><rect fill="url(#iXFOG5c)" transform="rotate(-45 11.632 18.66)" class="o4yzuw49p"/><rect fill="url(#iowzKoJ)" transform="rotate(-45 11.632 18.66)" class="o4yzuw49p"/><rect fill="url(#ifGoh2b)" transform="rotate(-45 11.632 18.66)" class="o4yzuw49p"/><defs><linearGradient id="iWgdxCm" x1="18.093" x2="27.906" y1="18.98" y2="28.855" gradientUnits="userSpaceOnUse"><stop class="ikwstpbcd"/><stop offset="1" class="ze3_hob-k"/></linearGradient><linearGradient id="ikw7fjg" x1="15.796" x2="25.958" y1="22.553" y2="19.97" gradientUnits="userSpaceOnUse"><stop class="q20vm19ud"/><stop offset="1" class="zqn3-690v"/></linearGradient><linearGradient id="ilsZecd" x1="17.023" x2="18.282" y1="17.013" y2="18.271" gradientUnits="userSpaceOnUse"><stop offset=".185" class="a7gu2pbxb"/><stop offset="1" class="uox434bxu"/></linearGradient><linearGradient id="i5fzuCd" x1="3.625" x2="4.359" y1="3.479" y2="4.198" gradientUnits="userSpaceOnUse"><stop offset=".024" class="z2w097bry"/><stop offset="1" class="kndpz0x0w"/></linearGradient><linearGradient id="iwmNxge" x1="15.812" x2="13.89" y1="16.292" y2="14.37" gradientUnits="userSpaceOnUse"><stop offset=".358" class="agj1w8t9h"/><stop offset="1" class="yuhxerb-o"/></linearGradient><linearGradient id="i0nknHc" x1="20.578" x2="27.846" y1="17.611" y2="24.879" gradientUnits="userSpaceOnUse"><stop class="ppnljsbyk"/><stop offset="1" class="egh0_dbhd"/></linearGradient><linearGradient id="ittHtAd" x1="19.871" x2="28.554" y1="16.904" y2="25.586" gradientUnits="userSpaceOnUse"><stop class="ikakd63kj"/><stop offset="1" class="kncghfvho"/></linearGradient><linearGradient id="i1Uy1gb" x1="20.322" x2="20.322" y1="17.761" y2="28.418" gradientUnits="userSpaceOnUse"><stop class="j3h7__9fz"/><stop offset="1" class="tebu46bli"/></linearGradient><linearGradient id="iHSFWRf" x1="17.057" x2="17.057" y1="20.584" y2="32.909" gradientUnits="userSpaceOnUse"><stop class="yajbvybel"/><stop offset="1" class="l35zkpbia"/></linearGradient><linearGradient id="iWYlCKe" x1="17.259" x2="17.259" y1="20.604" y2="31.995" gradientUnits="userSpaceOnUse"><stop class="aq13mv9jm"/><stop offset="1" class="p4cbm38jd"/></linearGradient><linearGradient id="ig1hnsd" x1=".373" x2=".373" y1="0" y2="10.478" gradientUnits="userSpaceOnUse"><stop class="nw1jkhz5r"/><stop offset="1" class="x5cxmmdkm"/></linearGradient><linearGradient id="iXFOG5c" x1="18.317" x2="18.317" y1="21.863" y2="21.333" gradientUnits="userSpaceOnUse"><stop class="obx95s2nj"/><stop offset="1" class="jafu004uf"/></linearGradient><linearGradient id="iowzKoJ" x1="16.659" x2="16.659" y1="18.35" y2="19.742" gradientUnits="userSpaceOnUse"><stop class="y0eh6e5xu"/><stop offset="1" class="nm9hx3bal"/></linearGradient><filter id="iwOs2jb" width="16.181" height="16.681" x="14.513" y="13.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.317647 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24342"/></filter><filter id="iTmkd4e" width="16.377" height="16.378" x="2.333" y="2.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.572549 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24342"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.843137 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24342" result="effect2_innerShadow_18_24342"/></filter><filter id="ictg3yb" width="11.325" height="11.325" x="18.55" y="15.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24342" stdDeviation=".325"/></filter><filter id="iugPvhb" width="8.987" height="8.987" x="19.471" y="16.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24342" stdDeviation=".3"/></filter><filter id="igU6hLc" width="10.634" height="10.634" x="15.788" y="18.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24342" stdDeviation=".325"/></filter><filter id="iBLiCUd" width="9.417" height="9.417" x="16.396" y="19.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24342" stdDeviation=".25"/></filter><filter id="i6KxcZb" width="8.627" height="8.627" x="16.276" y="20.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24342" stdDeviation=".25"/></filter><radialGradient id="isaHQ1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.65625 .375 -.21684 1.53593 6.156 9.448)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="xm8mbzbvt"/><stop offset="1" class="kavlqvjxl"/></radialGradient><radialGradient id="ifG386D" cx="0" cy="0" r="1" gradientTransform="rotate(44.24 -9.744 19.042)scale(5.46468 .40424)" gradientUnits="userSpaceOnUse"><stop class="gk28o5obs"/><stop offset="1" class="fqb1jfbke"/></radialGradient><radialGradient id="i3xlEoL" cx="0" cy="0" r="1" gradientTransform="matrix(8.24221 .0221 -.01238 4.61855 12.925 21.465)" gradientUnits="userSpaceOnUse"><stop class="b63sabb9s"/><stop offset="1" class="ks-0g-eht"/></radialGradient><radialGradient id="ifGoh2b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.37522 0 0 -.83969 19.466 20.36)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="dao6dbbyn"/><stop offset="1" class="xswsojbdy"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:screwdriver" /></template>
<style>
.a54lbcbfa {
  width: 1.237px;
  height: 11.391px;
  x: 16.64px;
  y: 20.604px;
  rx: 0.619px;
}

.a7gu2pbxb {
  stop-color: var(--svg-color--e1045d, #E1045D);
}

.agj1w8t9h {
  stop-color: var(--svg-color--7c7073, #7C7073);
}

.aq13mv9jm {
  stop-color: var(--svg-color--f0278f, #F0278F);
}

.b63sabb9s {
  stop-color: var(--svg-color--d2299a, #D2299A);
}

.bgtzsu8xr {
  width: 2.114px;
  height: 12.325px;
  x: 16px;
  y: 20.584px;
  rx: 1.057px;
}

.cjm18vb6q {
  d: path("M2.98 4.14a.5.5 0 0 0-.074.612l2.32 3.83a.5.5 0 0 0 .387.239l1.264.105a1 1 0 0 1 .624.29l8.944 8.943l1.765-1.765l-8.994-8.995a1 1 0 0 1-.293-.678L8.89 5.573a.5.5 0 0 0-.242-.414L4.803 2.852a.5.5 0 0 0-.61.075z");
}

.dao6dbbyn {
  stop-color: var(--svg-color--ff678b, #FF678B);
}

.dt_dalb1v {
  fill: var(--svg-color--b9b3be, #B9B3BE);
  d: path("M2.98 4.14a.5.5 0 0 0-.074.612l2.32 3.83a.5.5 0 0 0 .387.239l1.264.105a1 1 0 0 1 .624.29l8.944 8.943l1.765-1.765l-8.994-8.995a1 1 0 0 1-.293-.678L8.89 5.573a.5.5 0 0 0-.242-.414L4.803 2.852a.5.5 0 0 0-.61.075z");
}

.egh0_dbhd {
  stop-color: var(--svg-color--ff335a, #FF335A);
}

.fqb1jfbke {
  stop-color: var(--svg-color--9b819f, #9B819F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gk28o5obs {
  stop-color: var(--svg-color--9b819f, #9B819F);
}

.ikakd63kj {
  stop-color: var(--svg-color--ff66b1, #FF66B1);
}

.ikwstpbcd {
  stop-color: var(--svg-color--ff509e, #FF509E);
}

.il7k-pbek {
  fill-rule: evenodd;
  d: path("m21.663 16.904l6.89 6.89a1.267 1.267 0 1 1-1.791 1.792l-6.89-6.89a1.267 1.267 0 1 1 1.79-1.792");
}

.ilqy-bb8f {
  d: path("M23.03 30.057a2 2 0 0 0 2.829 0l4.25-4.25a2 2 0 0 0 0-2.828l-8.005-8.004a1.75 1.75 0 0 0-2.475 0l-4.603 4.603a1.75 1.75 0 0 0 0 2.475z");
}

.j3h7__9fz {
  stop-color: var(--svg-color--ff65a8, #FF65A8);
}

.jafu004uf {
  stop-color: var(--svg-color--de1a88, #DE1A88);
  stop-opacity: 0;
}

.kavlqvjxl {
  stop-color: var(--svg-color--a095a4, #A095A4);
  stop-opacity: 0;
}

.kncghfvho {
  stop-color: var(--svg-color--ff667d, #FF667D);
}

.kndpz0x0w {
  stop-color: var(--svg-color--a4a09d, #A4A09D);
  stop-opacity: 0;
}

.ks-0g-eht {
  stop-color: var(--svg-color--ff4f64, #FF4F64);
}

.l35zkpbia {
  stop-color: var(--svg-color--ed2e59, #ED2E59);
}

.nm9hx3bal {
  stop-color: var(--svg-color--ea2c6b, #EA2C6B);
  stop-opacity: 0;
}

.nw1jkhz5r {
  stop-color: var(--svg-color--fb4092, #FB4092);
}

.o4yzuw49p {
  width: 10.01px;
  height: 3.049px;
  x: 11.632px;
  y: 18.659px;
  rx: 1.525px;
}

.obx95s2nj {
  stop-color: var(--svg-color--af0241, #AF0241);
}

.os53xgbig {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m28.66 23.689l-6.891-6.892a1.417 1.417 0 0 0-2.004 2.004l6.89 6.891a1.417 1.417 0 0 0 2.005-2.003Z");
}

.p4cbm38jd {
  stop-color: var(--svg-color--eb2b63, #EB2B63);
}

.ppnljsbyk {
  stop-color: var(--svg-color--ff399d, #FF399D);
}

.q20vm19ud {
  stop-color: var(--svg-color--de2e8a, #DE2E8A);
}

.r2kmcbbnl {
  width: 0.745px;
  height: 10.478px;
  rx: 0.373px;
}

.tdlmmb8ac {
  width: 0.857px;
  height: 10.657px;
  x: 19.893px;
  y: 17.761px;
  rx: 0.429px;
}

.tebu46bli {
  stop-color: var(--svg-color--ff5f7e, #FF5F7E);
}

.uox434bxu {
  stop-color: var(--svg-color--ed2786, #ED2786);
  stop-opacity: 0;
}

.x5cxmmdkm {
  stop-color: var(--svg-color--fd4574, #FD4574);
}

.xm8mbzbvt {
  stop-color: var(--svg-color--9573ad, #9573AD);
}

.xswsojbdy {
  stop-color: var(--svg-color--ff678b, #FF678B);
  stop-opacity: 0;
}

.y0eh6e5xu {
  stop-color: var(--svg-color--c25067, #C25067);
}

.yajbvybel {
  stop-color: var(--svg-color--ee2391, #EE2391);
}

.yuhxerb-o {
  stop-color: var(--svg-color--bab4bf, #BAB4BF);
  stop-opacity: 0;
}

.z2w097bry {
  stop-color: var(--svg-color--a4a09d, #A4A09D);
}

.ze3_hob-k {
  stop-color: var(--svg-color--ff426f, #FF426F);
}

.zqn3-690v {
  stop-color: var(--svg-color--de2e8a, #DE2E8A);
  stop-opacity: 0;
}

</style>
