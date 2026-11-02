<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q2cuex3iy"/><path class="qos-3mbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q2cuex3iy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 19v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-4c0-.155.036-.308.106-.447l1-2C4.848 8.069 6.307 7 8 7h8c1.693 0 3.152 1.069 3.894 2.553l1 2c.07.139.106.292.106.447v4c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1Zm9.382-8l-.171-.342l-.002-.004A3 3 0 0 0 15.528 9H8.472a3 3 0 0 0-2.681 1.654L5.618 11Z");
}

.qos-3mbai {
  d: path("M14 6h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2M3 13a1 1 0 0 1 0-2h.382l.724-1.447C4.848 8.069 6.307 7 8 7h8c1.693 0 3.152 1.069 3.894 2.553L20.618 11H21a1 1 0 0 1 0 2Zm15.382-2l-.276-.553C17.706 9.649 16.926 9 16 9H8c-.926 0-1.706.649-2.106 1.447L5.618 11ZM8 14h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
