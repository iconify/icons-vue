<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyso2zwjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:work-update-outline" /></template>
<style>
.dyso2zwjx {
  fill: currentColor;
  d: path("M4 19v-.375zV8zm0 2q-.825 0-1.412-.587T2 19V8q0-.825.588-1.412T4 6h4V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h4q.825 0 1.413.588T22 8v4.275q-.45-.325-.95-.562T20 11.3V8H4v11h7.075q.075.525.225 1.025t.375.975zm6-15h4V4h-4zm4.463 15.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M18 21l3-3l-.7-.7l-1.8 1.8V15h-1v4.1l-1.8-1.8l-.7.7z");
}

</style>
