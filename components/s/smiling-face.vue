<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGJOv7obCd" cx="64" cy="-568" r="56.96" fx="64" fy="-568" gradientTransform="matrix(1 0 0 -1 0 -504)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".919" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGf7kNJclC" cx="18.061" cy="267.446" r="23.667" fx="18.061" fy="267.446" gradientTransform="matrix(.97908 0 0 .93012 12.779 -176.51)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="xxl2uvnsa"/><stop offset=".197" class="popcf8e5b"/><stop offset=".474" class="l8y_lcbgu"/><stop offset=".845" class="a44b3qwyn"/><stop offset="1" class="he1ha19dv"/></radialGradient><radialGradient id="SVGZKuFJddC" cx="86.57" r="23.667" fx="86.57" href="#SVGf7kNJclC"/></defs><path fill="url(#SVGJOv7obCd)" class="uuo0vn6ns"/><path class="km4-lkoid"/><circle fill="url(#SVGf7kNJclC)" class="tdmhzqb0h"/><circle fill="url(#SVGZKuFJddC)" class="v_v15ugcc"/><path class="wmawesqpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:smiling-face" /></template>
<style>
.a44b3qwyn {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.098;
}

.he1ha19dv {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0;
}

.km4-lkoid {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.893 30.769C117.22 39.366 120 49.612 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.063 0-37.037-7.347-48.179-22.94C24.583 111.623 44.811 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.742-3.471-24.06-10.107-33.231");
}

.l8y_lcbgu {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.314;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.popcf8e5b {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.449;
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.tdmhzqb0h {
  cx: 30.462px;
  cy: 72.247px;
  r: 23.096px;
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.v_v15ugcc {
  cx: 97.538px;
  cy: 72.247px;
  r: 23.096px;
}

.wmawesqpc {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M50.763 40.273c2.573.718 4.325-2.437 1.871-3.9c-1.803-1.075-3.696-1.547-5.678-1.832c-5.898-.76-11.313.5-15.43 3.507c-2.019 1.475-1.05 4.484 1.937 3.128c5.64-2.56 9.774-3.003 17.3-.903m26.474 0c-2.573.718-4.325-2.437-1.871-3.9c1.803-1.075 3.696-1.547 5.678-1.832c5.898-.76 11.313.5 15.43 3.507c2.019 1.475 1.05 4.484-1.937 3.128c-5.64-2.56-9.774-3.003-17.3-.903M64 100.296c10.273 0 16.93-7.9 18.738-11.6c.666-1.4.666-2.6.095-3.1q-.713-.6-1.997 0c-.286.1-.571.3-.856.5c-4.566 3.4-10.178 5.5-15.98 5.5s-11.414-2.1-15.98-5.4c-.285-.2-.57-.4-.856-.5q-1.284-.6-1.997 0c-.57.6-.57 1.7.095 3.1c1.807 3.6 8.465 11.5 18.738 11.5M53.996 55.775c-2.42-2.652-7.074-4.286-12.554-3.649c-5.132.597-9.323 3.086-11.324 6.675c-.987 1.77-.804 3.22.043 3.96c1.172 1.023 2.894.79 4.394.04c3.09-1.543 4.97-2.042 8.044-2.239s4.49.066 7.703 1.335c1.56.617 3.93.728 4.85-.805c.88-1.467.345-3.673-1.156-5.317m20.008 0c2.42-2.652 7.074-4.286 12.554-3.649c5.132.597 9.323 3.086 11.324 6.675c.987 1.77.804 3.22-.043 3.96c-1.172 1.023-2.894.79-4.394.04c-3.09-1.543-4.97-2.042-8.044-2.239s-4.49.066-7.703 1.335c-1.56.617-3.93.728-4.85-.805c-.88-1.467-.345-3.673 1.156-5.317");
}

.xxl2uvnsa {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.5;
}

</style>
