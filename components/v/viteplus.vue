<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":75};
const content = `<defs><filter id="SVGlw3PKbZz" width="19.25" height="13.354" x="76.528" y="5.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="2.455"/></filter><filter id="SVG4BYS2bLl" width="28.963" height="16.49" x="65.358" y="-2.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="2.455"/></filter><filter id="SVG5XhadcPx" width="25.44" height="9.425" x="66.952" y=".898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVG7olWyb5t" width="25.512" height="9.425" x="68.425" y="6.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGHGa8Hr4T" width="25.512" height="9.425" x="68.917" y="7.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGT1LPheWL" width="23.964" height="18.867" x="87.918" y="-5.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="2.455"/></filter><filter id="SVGE7rt7bWL" width="19.676" height="8.131" x="90.416" y=".979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGhr5Wlcos" width="17.967" height="20.405" x="74.007" y="-7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGX2UIYODV" width="17.573" height="20.725" x="89.315" y="-12.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGkNruMFDJ" width="12.355" height="13.008" x="89.793" y="-3.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGt4vHldfO" width="17.573" height="20.725" x="73.477" y="2.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGV5u1scJk" width="17.6" height="20.738" x="85.425" y="-.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter><filter id="SVGYjSoVgIC" width="15.135" height="17.016" x="88.093" y="2.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_19217" stdDeviation="1.473"/></filter></defs><path class="i11muti4h"/><path class="woq-86bpo"/><mask id="SVGYDsRzdnJ" width="17" height="15" x="82" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ji_brgips"/></mask><g mask="url(#SVGYDsRzdnJ)" transform="translate(.003 .127)scale(4.98276)"><g filter="url(#SVGlw3PKbZz)"><ellipse transform="rotate(89.814 35.525 46.024)scale(1 -1)" class="s5mcvh_6i"/></g><g filter="url(#SVG4BYS2bLl)"><ellipse transform="rotate(89.814 33.737 36.63)scale(1 -1)" class="kypiigulp"/></g><g filter="url(#SVG5XhadcPx)"><ellipse transform="rotate(89.814 33.002 36.998)scale(1 -1)" class="c0lhq5b4d"/></g><g filter="url(#SVG7olWyb5t)"><ellipse transform="rotate(89.814 30.844 40.622)scale(1 -1)" class="jts0aq-xu"/></g><g filter="url(#SVGHGa8Hr4T)"><ellipse transform="rotate(89.814 30.905 41.053)scale(1 -1)" class="jts0aq-xu"/></g><g filter="url(#SVGT1LPheWL)"><ellipse transform="rotate(93.35 49.173 54.748)scale(-1 1)" class="samjuir4x"/></g><g filter="url(#SVGE7rt7bWL)"><ellipse transform="rotate(89.009 50.51 57.537)scale(-1 1)" class="blavzzbev"/></g><g filter="url(#SVGE7rt7bWL)"><ellipse transform="rotate(89.009 50.51 57.537)scale(-1 1)" class="blavzzbev"/></g><g filter="url(#SVGhr5Wlcos)"><ellipse transform="rotate(39.51 82.99 3.123)" class="qle22mbrs"/></g><g filter="url(#SVGX2UIYODV)"><ellipse transform="rotate(37.892 98.101 -1.706)" class="l0nyfj4sp"/></g><g filter="url(#SVGkNruMFDJ)"><ellipse transform="rotate(37.892 95.97 3.395)" class="gevv-ibqv"/></g><g filter="url(#SVGt4vHldfO)"><ellipse transform="rotate(37.892 82.263 12.536)" class="v6x87acdn"/></g><g filter="url(#SVGt4vHldfO)"><ellipse transform="rotate(37.892 82.263 12.536)" class="v6x87acdn"/></g><g filter="url(#SVGV5u1scJk)"><ellipse transform="rotate(37.892 94.226 9.78)" class="m_5yz19im"/></g><g filter="url(#SVGYjSoVgIC)"><ellipse transform="rotate(37.892 95.66 10.827)" class="hvwwkacze"/></g></g><path class="v8pr3acye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:viteplus" /></template>
<style>
.blavzzbev {
  cx: 1.113px;
  cy: 6.893px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.113px;
  ry: 6.893px;
}

.c0lhq5b4d {
  cx: 1.766px;
  cy: 9.774px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.766px;
  ry: 9.774px;
}

.gevv-ibqv {
  cx: 95.97px;
  cy: 3.395px;
  fill: var(--svg-color--2bfdd2, #2bfdd2);
  rx: 2.655px;
  ry: 4.005px;
}

.hvwwkacze {
  cx: 95.66px;
  cy: 10.827px;
  fill: var(--svg-color--2bfdd2, #2bfdd2);
  rx: 2.578px;
  ry: 6.754px;
}

.i11muti4h {
  d: path("m45.526 53.399l18.79-52.034h25.705L61.525 73.629H28.489L.003 1.365h26.424zm77.841 20.23H98.591V1.365h24.776zm89.984-54.505H185.58v54.505h-24.773V19.124h-27.769V1.365h80.313zm81.004-.204h-46.56v9.701h45.837v17.031h-45.837V56.08h47.899v17.549h-72.672V1.365h71.333zm54.475 9.701h27.775v17.031H348.83v27.977h-17.753V45.652h-27.769V28.621h27.769V1.365h17.753z");
}

.ji_brgips {
  fill: var(--svg-color--833bff, #833bff);
  d: path("M91.184 14.654a.363.363 0 0 1-.648-.224v-3.303c0-.4-.324-.725-.725-.725h-3.647c-.295 0-.467-.334-.295-.573l2.398-3.357a.725.725 0 0 0-.59-1.147h-4.414c-.295 0-.467-.334-.295-.574L86.076.4a.36.36 0 0 1 .295-.152h9.263c.295 0 .467.334.295.573l-2.398 3.358a.725.725 0 0 0 .59 1.147h3.648c.302 0 .472.348.285.587z");
}

.jts0aq-xu {
  cx: 1.766px;
  cy: 9.81px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.766px;
  ry: 9.81px;
}

.kypiigulp {
  cx: 3.334px;
  cy: 9.57px;
  fill: var(--svg-color--ede6ff, #ede6ff);
  rx: 3.334px;
  ry: 9.57px;
}

.l0nyfj4sp {
  cx: 98.101px;
  cy: -1.706px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.413px;
  ry: 9.332px;
}

.m_5yz19im {
  cx: 94.226px;
  cy: 9.781px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.501px;
  ry: 9.332px;
}

.qle22mbrs {
  cx: 82.99px;
  cy: 3.123px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.413px;
  ry: 9.332px;
}

.s5mcvh_6i {
  cx: 1.766px;
  cy: 4.714px;
  fill: var(--svg-color--ede6ff, #ede6ff);
  rx: 1.766px;
  ry: 4.714px;
}

.samjuir4x {
  cx: 4.511px;
  cy: 7.078px;
  fill: var(--svg-color--ede6ff, #ede6ff);
  rx: 4.511px;
  ry: 7.078px;
}

.v6x87acdn {
  cx: 82.263px;
  cy: 12.536px;
  fill: var(--svg-color--4e14ff, #4e14ff);
  rx: 1.413px;
  ry: 9.332px;
}

.v8pr3acye {
  d: path("M401.264.128c-14.693 21.032-14.779 53.634 0 74.742h9.932c-14.78-21.108-14.69-53.71 0-74.742zm99.716 0h-9.931c14.699 21.032 14.783 53.634 0 74.742h9.931c14.778-21.108 14.688-53.71 0-74.742");
}

.woq-86bpo {
  fill: var(--svg-color--6254fe, #6254fe);
  d: path("M454.351 73.146c-1.061 1.35-3.229.597-3.229-1.116V55.572a3.61 3.61 0 0 0-3.613-3.613h-18.171c-1.471 0-2.327-1.664-1.471-2.856l11.949-16.726c1.708-2.392 0-5.721-2.945-5.721h-21.994c-1.465 0-2.322-1.658-1.465-2.854l15.487-21.685a1.81 1.81 0 0 1 1.47-.757h46.155c1.47 0 2.327 1.664 1.47 2.854l-11.948 16.727c-1.71 2.393 0 5.715 2.944 5.715h18.172c1.505 0 2.352 1.74 1.42 2.925l-34.231 43.571z");
}

</style>
