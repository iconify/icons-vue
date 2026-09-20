<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":157};
const content = `<path class="op_kfnb0l"/><g mask="url(#SVGboDTmdAz)" transform="translate(-1590.885 .03)scale(10.44884)"><g filter="url(#SVGqbs30cLI)"><ellipse transform="rotate(30.253 98.293 324.258)scale(-1 1)" class="p2gygq5wq"/></g><g filter="url(#SVGDnQAWdQe)"><ellipse transform="rotate(30.253 84.484 327.26)scale(-1 1)" class="p2gygq5wq"/></g><g filter="url(#SVG7sjEHb6F)"><ellipse transform="rotate(-36.093 157.853 .464)" class="diad37bfl"/></g><g filter="url(#SVGp2Q6qcaW)"><ellipse transform="rotate(-36.093 159.695 10.934)" class="cepuwjbtz"/></g><g filter="url(#SVGL3LIobkA)"><ellipse transform="rotate(36.093 94.989 268.152)scale(-1 1)" class="n2xctvbuh"/></g><g filter="url(#SVGTg3MFd6c)"><ellipse transform="rotate(36.093 77.817 269.997)scale(-1 1)" class="n2xctvbuh"/></g><g filter="url(#SVGBMx5xbgU)"><ellipse transform="rotate(36.093 94.437 266.458)scale(-1 1)" class="n2xctvbuh"/></g><g filter="url(#SVGIx0vCbap)"><ellipse transform="rotate(-143.907 87.6 -25.234)scale(1 -1)" class="n2xctvbuh"/></g><g filter="url(#SVGci62OeUs)"><ellipse transform="rotate(-40.91 158.534 .97)" class="ev5_u0b2d"/></g><g filter="url(#SVGNITUyfid)"><ellipse transform="rotate(-35.888 159.711 9.138)" class="chw8u4b0e"/></g></g><path class="wraa7lbdf"/><mask id="SVGboDTmdAz" width="15" height="15" x="157" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="wehnspbbn"/></mask><defs><filter id="SVGqbs30cLI" width="12.605" height="17.598" x="165.149" y="-8.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGDnQAWdQe" width="12.605" height="17.598" x="164.781" y="-1.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVG7sjEHb6F" width="12.89" height="15.819" x="151.408" y="-7.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGp2Q6qcaW" width="12.89" height="15.819" x="153.25" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGL3LIobkA" width="12.89" height="15.819" x="164.668" y="-7.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGTg3MFd6c" width="12.89" height="15.819" x="162.459" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGBMx5xbgU" width="12.89" height="15.819" x="163.564" y="-7.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGIx0vCbap" width="12.89" height="15.819" x="161.722" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGci62OeUs" width="14.664" height="16.072" x="151.202" y="-7.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter><filter id="SVGNITUyfid" width="13.72" height="16.839" x="152.852" y=".718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_20995" stdDeviation="1.105"/></filter></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rolldown-icon" /></template>
<style>
.cepuwjbtz {
  cx: 159.695px;
  cy: 10.934px;
  fill: var(--svg-color--ff19af, #ff19af);
  rx: 1.192px;
  ry: 6.999px;
}

.chw8u4b0e {
  cx: 159.711px;
  cy: 9.138px;
  fill: var(--svg-color--d14b2a, #d14b2a);
  rx: 1.73px;
  ry: 7.56px;
}

.diad37bfl {
  cx: 157.853px;
  cy: 0.464px;
  fill: var(--svg-color--ff19af, #ff19af);
  rx: 1.192px;
  ry: 6.999px;
}

.ev5_u0b2d {
  cx: 158.534px;
  cy: 0.97px;
  fill: var(--svg-color--d14b2a, #d14b2a);
  rx: 1.73px;
  ry: 7.56px;
}

.n2xctvbuh {
  cx: 1.192px;
  cy: 6.999px;
  fill: var(--svg-color--ff19af, #ff19af);
  rx: 1.192px;
  ry: 6.999px;
}

.op_kfnb0l {
  fill: var(--svg-color--f50, #f50);
  d: path("M187.855 2.618c3.199 0 4.956 3.741 2.896 6.212l-34.979 41.988c-4.116 4.924-.602 12.423 5.822 12.423h33.85c3.2 0 4.957 3.751 2.897 6.212l-67.697 81.241c-1.511 1.815-4.31 1.815-5.818 0l-67.7-81.241c-2.046-2.461-.3-6.212 2.911-6.212h33.828c6.425 0 9.938-7.499 5.829-12.423L64.715 8.83c-2.059-2.471-.299-6.212 2.901-6.212z");
}

.p2gygq5wq {
  cx: 1.73px;
  cy: 7.56px;
  fill: var(--svg-color--ffe7e5, #ffe7e5);
  rx: 1.73px;
  ry: 7.56px;
}

.wehnspbbn {
  d: path("M170.233.248c.307 0 .475.358.278.594l-3.348 4.018a.725.725 0 0 0 .557 1.19h3.239c.307 0 .475.359.278.595l-6.479 7.775a.362.362 0 0 1-.557 0l-6.479-7.775a.363.363 0 0 1 .279-.595h3.237a.726.726 0 0 0 .558-1.19L158.448.842a.362.362 0 0 1 .278-.594z");
}

.wraa7lbdf {
  fill: var(--svg-color--08060d, #08060d);
  d: path("M23.189.032c-30.816 44.102-30.993 112.473 0 156.73h20.81c-30.971-44.257-30.795-112.628 0-156.73zm209.103 0h-20.821c30.806 44.102 30.983 112.473 0 156.73h20.821c30.983-44.257 30.802-112.628 0-156.73");
}

</style>
