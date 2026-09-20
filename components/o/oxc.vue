<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":94};
const content = `<path class="h3biz82jp"/><path class="r203_dbjs"/><g mask="url(#SVG49sixe3w)" transform="translate(.187 .016)scale(6.26773)"><g filter="url(#SVGJB18t4me)"><ellipse transform="matrix(0 -1 -1 0 76.277 16.466)" class="cueu5v0si"/></g><g filter="url(#SVG19HEngWm)"><ellipse transform="rotate(68.34 31.37 67.115)scale(-1 1)" class="jdfzn5b9a"/></g><g filter="url(#SVGxujnsdAY)"><ellipse transform="rotate(-68.34 63.551 14.356)" class="zjrnxvbvv"/></g><g filter="url(#SVGKlLVzdmj)"><ellipse transform="rotate(-135.197 72.12 9.509)" class="b819jik8y"/></g><g filter="url(#SVGX5xtgdvL)"><ellipse transform="rotate(-135.197 72.733 8.404)" class="e1568vbnt"/></g><g filter="url(#SVGOGaF6dFQ)"><ellipse transform="rotate(-135.197 72.61 2.265)" class="iywbiwbsc"/></g><g filter="url(#SVGRfIfmeOo)"><ellipse transform="rotate(-135.197 72.98 1.774)" class="t51amubwb"/></g><g filter="url(#SVGOSPApc1f)"><ellipse transform="rotate(-44.803 48.285 -75.76)scale(1 -1)" class="u-3hz9e-l"/></g><g filter="url(#SVGOeXnqeFs)"><ellipse transform="rotate(-44.803 46.515 -75.27)scale(1 -1)" class="emlz3gbcg"/></g><g filter="url(#SVG4jdRld0e)"><ellipse transform="rotate(135.197 32.342 15.982)scale(-1 1)" class="u-3hz9e-l"/></g><g filter="url(#SVGlxXNEbeJ)"><ellipse transform="rotate(-44.803 37.816 -78.68)scale(1 -1)" class="emlz3gbcg"/></g><g filter="url(#SVGRTw3gelQ)"><ellipse transform="rotate(-44.803 44.79 -76.156)scale(1 -1)" class="nee1-2b1k"/></g><g filter="url(#SVGtozOldvZ)"><ellipse transform="rotate(-135.197 74.385 4.902)" class="mj4z_9c4i"/></g><g filter="url(#SVGnNpsNefx)"><ellipse transform="matrix(0 -1 -1 0 76.277 17.08)" class="e5spo130t"/></g></g><path class="yi82ogbqj"/><mask id="SVG49sixe3w" width="16" height="15" x="61" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="fcz167bdp"/></mask><defs><filter id="SVGJB18t4me" width="19.679" height="8.854" x="59.545" y="10.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVG19HEngWm" width="18.753" height="11.679" x="65.838" y="8.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGxujnsdAY" width="18.753" height="11.679" x="54.175" y="8.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGKlLVzdmj" width="9.192" height="9.203" x="67.524" y="4.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGX5xtgdvL" width="9.192" height="9.203" x="68.137" y="3.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOGaF6dFQ" width="9.192" height="9.203" x="68.014" y="-2.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGRfIfmeOo" width="9.192" height="9.203" x="68.383" y="-2.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOSPApc1f" width="9.192" height="9.203" x="62.244" y="5.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGOeXnqeFs" width="9.192" height="9.203" x="61.385" y="4.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVG4jdRld0e" width="9.192" height="9.203" x="61.385" y="-2.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGlxXNEbeJ" width="9.192" height="9.203" x="61.261" y="-3.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGRTw3gelQ" width="11.551" height="11.584" x="59.045" y=".092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGtozOldvZ" width="11.551" height="11.584" x="68.609" y="-.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter><filter id="SVGnNpsNefx" width="19.679" height="8.854" x="59.545" y="11.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_242_21098" stdDeviation="1.473"/></filter></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:oxc" /></template>
<style>
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

.h3biz82jp {
  fill: var(--svg-color--08060d, #08060d);
  d: path("M58.494.017c38.307 0 58.434 16.103 58.435 47.008c0 30.905-20.128 47.007-58.435 47.007S.187 77.93.187 47.025c0-30.906 20-47.008 58.307-47.008m228.073 0c34.281 0 55.056 13.504 55.058 39.344v.264H308.64v-.264c-.002-11.166-6.881-17.009-22.073-17.01c-17.27 0-25.45 7.792-25.45 24.674s8.18 24.544 25.45 24.544c15.193 0 22.072-5.845 22.073-16.882v-.127h32.985v.127c-.001 25.58-20.128 39.344-55.058 39.345c-37.657 0-57.265-16.232-57.265-47.007c0-30.776 19.608-47.008 57.265-47.008m-113.498 29.22l19.477-27.66h34.282l-32.593 44.407l33.763 46.487h-35.71l-21.165-29.735l-20.78 29.735H116.06l33.762-46.744L117.1 1.577h36.101zM58.494 22.351c-18.05 0-26.492 7.663-26.492 24.674s8.442 24.544 26.492 24.544c18.049 0 26.49-7.664 26.49-24.544c0-17.011-8.441-24.673-26.49-24.674");
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

.r203_dbjs {
  fill: var(--svg-color--32f3ef, #32f3ef);
  d: path("M448.974 15.201a4.545 4.545 0 0 0 4.545 4.546h17.244c2.026 0 3.039 2.449 1.607 3.877l-22.068 22.068a4.55 4.55 0 0 0-1.332 3.216v7.545c0 3.137 3.112 5.315 5.865 3.817a41 41 0 0 0 7.774-5.48c.934-.835 2.372-.844 3.259.047L481.94 70.91c.887.887.892 2.327-.027 3.185c-12.188 11.406-28.572 18.392-46.583 18.392s-34.394-6.986-46.582-18.392c-.919-.858-.915-2.298-.027-3.185l16.072-16.073c.887-.887 2.325-.882 3.259-.047a41 41 0 0 0 7.774 5.48c2.758 1.498 5.866-.68 5.866-3.817v-7.545a4.55 4.55 0 0 0-1.334-3.216l-22.067-22.068c-1.433-1.432-.419-3.877 1.607-3.877h17.244a4.546 4.546 0 0 0 4.546-4.546V3.835a2.27 2.27 0 0 1 2.272-2.273h22.728a2.27 2.27 0 0 1 2.272 2.273v11.366z");
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

.yi82ogbqj {
  fill: var(--svg-color--08060d, #08060d);
  d: path("M372.623.017c-18.483 26.456-18.592 67.465 0 94.015h12.487c-18.586-26.55-18.478-67.559 0-94.015zm125.426 0h-12.487c18.482 26.456 18.591 67.465 0 94.015h12.487c18.588-26.55 18.479-67.559 0-94.015");
}

.zjrnxvbvv {
  cx: 63.551px;
  cy: 14.356px;
  fill: var(--svg-color--195eff, #195eff);
  rx: 1.48px;
  ry: 6.893px;
}

</style>
