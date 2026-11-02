<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tw7y6mbhw"/><path class="a8luhacgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-bulk-sharp" /></template>
<style>
.a8luhacgk {
  d: path("M18.789 4.386a12.395 12.395 0 0 1 0 15.228a1 1 0 1 1-1.578-1.228a10.3 10.3 0 0 0 1.643-3.052c.364-1.074.549-2.2.548-3.334a10.4 10.4 0 0 0-.548-3.334a10.3 10.3 0 0 0-1.643-3.052a.999.999 0 1 1 1.578-1.228m-2.957 3.059a8.21 8.21 0 0 1 0 9.11a1 1 0 1 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1.002 1.002 0 0 1 .638-1.536c.397-.078.802.09 1.026.426");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tw7y6mbhw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4");
}

</style>
