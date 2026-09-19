<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="lv6q5yolh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:petlibro" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lv6q5yolh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.7 22.402h-6.2v3.195m-3.368 6.535l4.384 4.384M14.371 17.365l-4.384-4.384l1.48-1.48c.836-.836 2.173-.855 2.986-.041c.813.813.794 2.15-.042 2.986l-1.48 1.48m4.434 17.703l-4.384 4.384l-1.48-1.48c-.836-.836-.855-2.173-.041-2.986c.813-.813 2.15-.794 2.986.042l1.48 1.48m-1.48-1.481l-.042-2.918m20.683-20.614l2.857 2.857m-5.812 2.955l4.384-4.384M22.402 9.4h2.077m1.119 3.1h-3.195V6.3h3.195m-2.121 32.3c-.882 0-1.598-.694-1.598-1.55s.716-1.55 1.598-1.55h2.636v6.2h-2.636c-.882 0-1.598-.694-1.598-1.55s.716-1.55 1.598-1.55m0 0h2.633M6.3 24c0-1.173.916-2.117 2.054-2.117h2.092c1.138 0 2.054.944 2.054 2.117s-.916 2.117-2.054 2.117H8.354C7.216 26.117 6.3 25.173 6.3 24");
}

</style>
