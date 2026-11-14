<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-mvib4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:music-venue" /></template>
<style>
.f6-mvib4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.854 3.295L3.979 8.133q-1.23 1.013-1.229 2.606v7.636q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-7.636q.001-1.593-1.229-2.606l-5.875-4.838q-2.146-1.768-4.292 0m2.164 14.973Q11.286 19 10.25 19q-2.5 0-2.5-2.5t2.5-2.5q.541 0 1 .2V9.5q0-.182.084-.344l.015-.028q.049-.086.119-.157q.07-.07.156-.12t.181-.075q.096-.026.195-.026q.182 0 .344.084l.028.015l3.5 2q.064.036.12.085q.056.048.101.107t.078.124t.053.138q.019.071.024.145q.005.073-.004.147q-.009.073-.033.143q-.023.07-.06.134q-.036.064-.085.12q-.048.056-.107.101t-.124.078q-.066.033-.138.053q-.071.019-.145.024q-.073.005-.147-.004q-.073-.009-.143-.033q-.07-.023-.134-.06l-2.378-1.359V16.5q0 1.036-.732 1.768");
}

</style>
