<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w58e2tb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save-outline" /></template>
<style>
.w58e2tb8p {
  fill: currentColor;
  d: path("M20 7.423v10.962q0 .69-.462 1.153T18.384 20H5.616q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h10.961zm-1 .427L16.15 5H5.616q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443zm-5.587 8.102q.587-.586.587-1.414t-.587-1.413T12 12.539t-1.413.586T10 14.538t.587 1.414t1.413.586t1.414-.586M6.768 9.769h7.423v-3H6.77zM5 7.85V19V5z");
}

</style>
