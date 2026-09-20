<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r1oqymaaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-chat-20-filled" /></template>
<style>
.r1oqymaaf {
  fill: currentColor;
  d: path("M6.5 2A1.5 1.5 0 0 0 5 3.5v13A1.5 1.5 0 0 0 6.5 18h2.617l.373-1.227A5.5 5.5 0 0 1 15 9.023V3.5A1.5 1.5 0 0 0 13.5 2zm8 17a4.5 4.5 0 1 0-3.937-2.318l-.544 1.789a.41.41 0 0 0 .51.51l1.79-.544A4.5 4.5 0 0 0 14.5 19M12 13.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5m.5 2.5a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1z");
}

</style>
