<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":157};
const content = `<path class="ihjx71-2y"/><g mask="url(#SVG49sixe3w)" transform="translate(-597.868 .032)scale(10.45498)"><g filter="url(#SVGJB18t4me)"><ellipse transform="matrix(0 -1 -1 0 76.277 16.466)" class="cueu5v0si"/></g><g filter="url(#SVG19HEngWm)"><ellipse transform="rotate(68.34 31.37 67.115)scale(-1 1)" class="jdfzn5b9a"/></g><g filter="url(#SVGxujnsdAY)"><ellipse transform="rotate(-68.34 63.551 14.356)" class="zjrnxvbvv"/></g><g filter="url(#SVGKlLVzdmj)"><ellipse transform="rotate(-135.197 72.12 9.509)" class="b819jik8y"/></g><g filter="url(#SVGX5xtgdvL)"><ellipse transform="rotate(-135.197 72.733 8.404)" class="e1568vbnt"/></g><g filter="url(#SVGOGaF6dFQ)"><ellipse transform="rotate(-135.197 72.61 2.265)" class="iywbiwbsc"/></g><g filter="url(#SVGRfIfmeOo)"><ellipse transform="rotate(-135.197 72.98 1.774)" class="t51amubwb"/></g><g filter="url(#SVGOSPApc1f)"><ellipse transform="rotate(-44.803 48.285 -75.76)scale(1 -1)" class="u-3hz9e-l"/></g><g filter="url(#SVGOeXnqeFs)"><ellipse transform="rotate(-44.803 46.515 -75.27)scale(1 -1)" class="emlz3gbcg"/></g><g filter="url(#SVG4jdRld0e)"><ellipse transform="rotate(135.197 32.342 15.982)scale(-1 1)" class="u-3hz9e-l"/></g><g filter="url(#SVGlxXNEbeJ)"><ellipse transform="rotate(-44.803 37.816 -78.68)scale(1 -1)" class="emlz3gbcg"/></g><g filter="url(#SVGRTw3gelQ)"><ellipse transform="rotate(-44.803 44.79 -76.156)scale(1 -1)" class="nee1-2b1k"/></g><g filter="url(#SVGtozOldvZ)"><ellipse transform="rotate(-135.197 74.385 4.902)" class="mj4z_9c4i"/></g><g filter="url(#SVGnNpsNefx)"><ellipse transform="matrix(0 -1 -1 0 76.277 17.08)" class="e5spo130t"/></g></g><path class="aryvvlqxz"/><mask id="SVG49sixe3w" width="16" height="15" x="61" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="fcz167bdp"/></mask><defs><filter id="SVGJB18t4me" width="19.679" height="8.854" x="59.545" y="10.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVG19HEngWm" width="18.753" height="11.679" x="65.838" y="8.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGxujnsdAY" width="18.753" height="11.679" x="54.175" y="8.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGKlLVzdmj" width="9.192" height="9.203" x="67.524" y="4.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGX5xtgdvL" width="9.192" height="9.203" x="68.137" y="3.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOGaF6dFQ" width="9.192" height="9.203" x="68.014" y="-2.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGRfIfmeOo" width="9.192" height="9.203" x="68.383" y="-2.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOSPApc1f" width="9.192" height="9.203" x="62.244" y="5.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOeXnqeFs" width="9.192" height="9.203" x="61.385" y="4.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVG4jdRld0e" width="9.192" height="9.203" x="61.385" y="-2.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGlxXNEbeJ" width="9.192" height="9.203" x="61.261" y="-3.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGRTw3gelQ" width="11.551" height="11.584" x="59.045" y=".092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGtozOldvZ" width="11.551" height="11.584" x="68.609" y="-.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGnNpsNefx" width="19.679" height="8.854" x="59.545" y="11.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:oxc-icon" /></template>
<style>
.aryvvlqxz {
  fill: var(--svg-color--08060d, #08060d);
  d: path("M23.38.033c-30.83 44.13-31.012 112.537 0 156.824h20.83C13.207 112.57 13.387 44.164 44.21.033zm209.22 0h-20.83c30.83 44.13 31.012 112.537 0 156.824h20.83c31.006-44.287 30.824-112.693 0-156.824");
}

.b819jik8y {
  cx: 72.12px;
  cy: 9.509px;
  fill: var(--svg-color--aefffb, #aefffb);
  rx: 1.191px;
  ry: 2.01px;
}

.cueu5v0si {
  cx: 1.48px;
  cy: 6.893px;
  fill: var(--svg-color--aefffb, #aefffb);
  rx: 1.48px;
  ry: 6.893px;
}

.e1568vbnt {
  cx: 72.733px;
  cy: 8.404px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.191px;
  ry: 2.01px;
}

.e5spo130t {
  cx: 1.48px;
  cy: 6.893px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.48px;
  ry: 6.893px;
}

.emlz3gbcg {
  cx: 1.191px;
  cy: 2.01px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.191px;
  ry: 2.01px;
}

.fcz167bdp {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M71.603 2.422c0 .401.325.726.725.726h2.751c.324 0 .485.39.257.618l-3.521 3.521a.73.73 0 0 0-.213.513v1.204c0 .5.497.848.936.609a6.5 6.5 0 0 0 1.24-.874a.38.38 0 0 1 .52.007l2.564 2.565a.353.353 0 0 1-.004.508a10.84 10.84 0 0 1-7.432 2.934a10.84 10.84 0 0 1-7.432-2.934a.353.353 0 0 1-.004-.508l2.564-2.565a.38.38 0 0 1 .52-.007c.376.337.793.631 1.24.874c.44.239.936-.108.936-.61V7.8a.73.73 0 0 0-.213-.513l-3.52-3.52a.362.362 0 0 1 .256-.62h2.751c.4 0 .725-.324.725-.725V.61c0-.2.163-.363.363-.363h3.626c.2 0 .363.163.363.363v1.813z");
}

.ihjx71-2y {
  fill: var(--svg-color--32f3ef, #32f3ef);
  d: path("M150.739 25.361a7.58 7.58 0 0 0 7.582 7.583h28.764c3.379 0 5.069 4.085 2.68 6.467l-36.811 36.811a7.58 7.58 0 0 0-2.221 5.364v12.586c0 5.233 5.191 8.866 9.783 6.367a68.5 68.5 0 0 0 12.967-9.141c1.558-1.393 3.957-1.408 5.437.078l26.809 26.811c1.479 1.48 1.488 3.882-.045 5.313c-20.331 19.026-47.66 30.679-77.704 30.679S70.609 142.626 50.278 123.6c-1.533-1.431-1.526-3.833-.045-5.313l26.809-26.811c1.48-1.479 3.879-1.471 5.437-.078a68.5 68.5 0 0 0 12.967 9.141c4.601 2.499 9.785-1.134 9.785-6.367V81.586a7.58 7.58 0 0 0-2.225-5.364L66.197 39.411c-2.391-2.389-.699-6.467 2.68-6.467h28.764a7.58 7.58 0 0 0 7.583-7.583V6.402a3.79 3.79 0 0 1 3.79-3.792h37.912a3.79 3.79 0 0 1 3.79 3.792v18.959z");
}

.iywbiwbsc {
  cx: 72.61px;
  cy: 2.265px;
  fill: var(--svg-color--aefffb, #aefffb);
  rx: 1.191px;
  ry: 2.01px;
}

.jdfzn5b9a {
  cx: 1.48px;
  cy: 6.893px;
  fill: var(--svg-color--0f8, #0f8);
  rx: 1.48px;
  ry: 6.893px;
}

.mj4z_9c4i {
  cx: 74.385px;
  cy: 4.902px;
  fill: var(--svg-color--0f8, #0f8);
  rx: 1.191px;
  ry: 3.831px;
}

.nee1-2b1k {
  cx: 1.191px;
  cy: 3.831px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.191px;
  ry: 3.831px;
}

.t51amubwb {
  cx: 72.979px;
  cy: 1.774px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.191px;
  ry: 2.01px;
}

.u-3hz9e-l {
  cx: 1.191px;
  cy: 2.01px;
  fill: var(--svg-color--aefffb, #aefffb);
  rx: 1.191px;
  ry: 2.01px;
}

.zjrnxvbvv {
  cx: 63.551px;
  cy: 14.356px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.48px;
  ry: 6.893px;
}

</style>
