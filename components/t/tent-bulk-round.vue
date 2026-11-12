<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bu8nd8kbn"/><path class="g9-7qlbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tent-bulk-round" /></template>
<style>
.bu8nd8kbn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.894 20.553A1 1 0 0 1 19 22h-4l-2.791-6.978a1 1 0 0 0-.418 0L9 22H5a1 1 0 0 1-.894-1.447l7-14a.998.998 0 0 1 1.788 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g9-7qlbdh {
  d: path("m13.118 7l6.5 13H21a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1.382l6.5-13l-1.776-3.553a1 1 0 1 1 1.788-.894L12 4.764l1.106-2.211a1 1 0 1 1 1.788.894Zm-.19 8.629L14.677 20h2.705L12 9.236L6.618 20h2.705l1.749-4.371a.998.998 0 0 1 1.856 0M12.523 20L12 18.693L11.477 20Z");
}

</style>
