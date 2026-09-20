<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wak557brd"/><path class="dvh9o7bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paint" /></template>
<style>
.dvh9o7bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.93 20.832a3.211 3.211 0 1 1-3.211-3.211a3.21 3.21 0 0 1 3.212 3.211m22.556 0a3.211 3.211 0 1 1-6.422 0a3.211 3.211 0 1 1 6.422 0m-6.043-8.215a3.211 3.211 0 0 1-6.422 0a3.211 3.211 0 1 1 6.422 0m-10.471 0a3.211 3.211 0 1 1-6.422 0a3.211 3.211 0 0 1 6.422 0");
}

.wak557brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.288 42.47C13.91 42.412 5.498 34.2 5.498 24S13.91 5.53 24.288 5.53c6.602 0 12.328 3.64 15.76 8.41c1.63 2.265 3.133 5.465 2.131 10.278c-1 4.813-5.944 7.888-8.723 7.888H28.95c-3.896 0-4.265 3.667-2.635 5.396c1.53 1.623.41 4.982-2.028 4.968");
}

</style>
