<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqB1AOdMQ)" class="vwzje453h"/><defs><linearGradient id="SVGqB1AOdMQ" x1="20.42" x2="5.227" y1="9.092" y2="16.382" gradientUnits="userSpaceOnUse"><stop offset=".03" class="yd2x-seks"/><stop offset=".61" class="y105d5b8t"/><stop offset="1" class="apxkel6ji"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solx" /></template>
<style>
.apxkel6ji {
  stop-color: var(--svg-color--20bdfc, #20bdfc);
}

.ft5dv1b6b {
  fill: none;
}

.vwzje453h {
  d: path("M18.367 8.625H14.25c0-1.485-1.553-2.194-2.25-2.25c-.793-.04-2.25.433-2.25 1.817c0 1.727.607 1.417 5.012 2.261c3.527.675 4.5 3.38 4.545 4.652c.112 1.969-1.17 5.895-7.2 5.895c-6.025 0-7.46-3.707-7.42-5.625h4.365c-.056 1.957 2.385 2.25 3.055 2.25c.675 0 2.705-.394 2.705-2.098s-1.67-1.62-2.323-1.665a27 27 0 0 1-1.614-.175c-4.388-.579-5.62-3.577-5.62-5.09C5.255 7.078 5.42 3 12 3c5.265 0 6.435 3.757 6.367 5.625");
}

.y105d5b8t {
  stop-color: var(--svg-color--483eff, #483eff);
}

.yd2x-seks {
  stop-color: var(--svg-color--e604b7, #e604b7);
}

</style>
