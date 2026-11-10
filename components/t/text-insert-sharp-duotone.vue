<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s_kw4pk0x"/><path class="l7v3biqup"/><path class="bpagb_jvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-insert-sharp-duotone" /></template>
<style>
.bpagb_jvu {
  d: path("M8.995 2L11.684 4.52C11.885 4.71 12 4.97 12 5.25C12 5.53 11.885 5.79 11.684 5.98L8.967 8.53L7.6 7.07L8.249 6.46L8.471 6.25H4V10H2V5.25C2 4.7 2.448 4.25 3 4.25H8.472L8.25 4.04L7.627 3.46L8.995 2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l7v3biqup {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 8V10H14V8H22ZM22 2V4H14V2H22Z");
}

.s_kw4pk0x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 20V22H2V20H22ZM22 14V16H2V14H22ZM8.995 2L11.684 4.52C11.885 4.71 12 4.97 12 5.25C12 5.53 11.885 5.79 11.684 5.98L8.967 8.53L7.6 7.07L8.249 6.46L8.471 6.25H4V10H2V5.25C2 4.7 2.448 4.25 3 4.25H8.472L8.25 4.04L7.627 3.46L8.995 2Z");
}

</style>
