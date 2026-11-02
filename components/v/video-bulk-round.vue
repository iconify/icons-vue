<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ilgp8dblk"/><path class="rvqnyobur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ilgp8dblk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.rvqnyobur {
  d: path("M16.553 8.106c1.12-.56 2.457-.597 3.583-.034c.534.267.996.658 1.328 1.154c.352.527.536 1.141.536 1.774v2c0 .633-.184 1.247-.536 1.774a3.44 3.44 0 0 1-1.328 1.154c-1.126.563-2.463.526-3.583-.034l-2-1a1 1 0 1 1 .894-1.788l2 1c.295.15.621.228.951.228C19.171 14.332 20 13.852 20 13v-2c0-.852-.829-1.332-1.602-1.334c-.33 0-.656.078-.951.228l-2 1a1 1 0 1 1-.894-1.788Z");
}

</style>
