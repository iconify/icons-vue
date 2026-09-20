<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cub-3abru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:media-output-sharp" /></template>
<style>
.cub-3abru {
  fill: currentColor;
  d: path("M10.23 21v-5.538q0-2.244 1.573-3.814q1.571-1.571 3.817-1.571t3.813 1.57T21 15.463V21h-2.77v-4.384h1.886v-1.154q0-1.875-1.313-3.188t-3.187-1.312t-3.188 1.312t-1.312 3.188v1.154H13V21zM9.544 8.118q.38-.382.38-.928t-.382-.926t-.928-.38t-.926.383t-.38.927q0 .546.383.926t.928.38t.925-.382M7.846 19H3V3h11.23v4.82q-1.366.251-2.531.924t-2.013 1.687q-.24-.09-.509-.145q-.27-.055-.561-.055q-1.323 0-2.258.935t-.935 2.257q0 1.139.69 1.986q.689.847 1.733 1.105zm.77-7.77q.125 0 .22.016q.097.015.222.046q-.542.862-.857 1.84q-.314.98-.337 2.082v.269q-.63-.24-1.035-.795q-.406-.554-.406-1.265q0-.913.64-1.553q.639-.64 1.553-.64");
}

</style>
