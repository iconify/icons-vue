<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybf5pwmvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-cottage" /></template>
<style>
.ybf5pwmvu {
  fill: currentColor;
  d: path("M22.39 12.19a.99.99 0 0 0-.19-1.4l-9.6-7.33c-.36-.27-.86-.27-1.21 0L6 7.58V7c0-.55-.45-1-1-1s-1 .45-1 1v2.11l-2.21 1.68c-.44.33-.52.96-.19 1.4c.34.44.96.52 1.4.19l1-.76V20c0 .55.45 1 1 1h6v-5c0-.55.45-1 1-1s1 .45 1 1v5h6c.55 0 1-.45 1-1v-8.38l.99.76c.44.34 1.07.25 1.4-.19M5.27 5c-.74 0-1.26-.8-.9-1.45C4.89 2.62 5.87 2 7 2c.38 0 .72-.22.89-.53c.15-.31.5-.47.84-.47c.74 0 1.26.8.9 1.45C9.11 3.38 8.13 4 7 4c-.38 0-.72.22-.89.53c-.15.31-.5.47-.84.47");
}

</style>
