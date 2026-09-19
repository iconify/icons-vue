<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1ssdgxir"/><path class="e8m70e7il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:memechat" /></template>
<style>
.e8m70e7il {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.189 10.133c-2.662-6.636 1.429-6.724 4.556-3.78c3.879 3.651 7.987 11.956 8.3 15.404c1.072 7.779.3 13.272-3.487 17.614c-4.434 4.554-9.444 4.474-14.246 3.775c-6.226-1.304-9.38-8.02-10.76-15.001c-.412-1.834 2.453-3.14 3.687-2.42c2.65 1.929 4.203 5.249 6.177 6.774c4.965 3.058 7.292-1.291 7.87-3.193c1.324-4.716-4.336-5.925-4.981-5.807c-5.477.215-5.012 2.27-8.767 1.548a3.1 3.1 0 0 1-2.39-3");
}

.j1ssdgxir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.147 22.047c.324-4.322 8.075-4.98 12.652-5.13m.001.001c.692.231-1.04-2.463-3.264-5.42c-2.014-3.51 3.517-3.75 4.653-1.365");
}

</style>
