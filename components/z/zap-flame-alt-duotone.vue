<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kg8p8ffjl"/><path class="fv4f-yp0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-alt-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv4f-yp0f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.333 11.333L4.138 14.53c-.137.137-.369.01-.327-.18l1.044-4.698A.535.535 0 0 0 4.333 9h-.666a.433.433 0 0 1-.396-.61l2.22-4.994A.67.67 0 0 1 6.1 3h3.567c.297 0 .483.32.336.579L7.997 7.088a.387.387 0 0 0 .336.579h2c.246 0 .37.297.196.471zM16 21c-5.667-4.667-1.667-8.667 1-12c2.667 3.333 6.667 7.333 1 12Zm0 0c-3-2.333-1.667-4.333 1-6.667c2.667 2.334 4 4.334 1 6.667");
}

.kg8p8ffjl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7.333 11.333l-3.195 3.196a.195.195 0 0 1-.231.033a.195.195 0 0 1-.096-.213l1.044-4.698A.534.534 0 0 0 4.333 9h-.666a.434.434 0 0 1-.396-.609l2.22-4.995A.67.67 0 0 1 6.1 3h3.567c.138 0 .265.073.334.193c.07.119.07.266.002.386L7.997 7.088a.386.386 0 0 0 .336.579h2a.276.276 0 0 1 .196.471Zm7.912 8.995c-4.187-4.05-1.3-7.583 1.165-10.601q.296-.361.59-.727q.294.366.59.727c2.465 3.018 5.352 6.551 1.165 10.601c1.133-1.18 1.26-2.371.364-3.736a6 6 0 0 0-.416-.561c-.51-.621-1.1-1.17-1.703-1.698c-.603.528-1.193 1.077-1.703 1.698a6 6 0 0 0-.416.561c-.896 1.365-.769 2.556.364 3.736");
}

</style>
