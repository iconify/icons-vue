<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g87ap4bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save-rounded" /></template>
<style>
.g87ap4bwg {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h10.29q.323 0 .628.13q.305.132.522.349l2.465 2.465q.218.218.348.522q.131.305.131.628v10.29q0 .691-.462 1.154T18.384 20zm7.798-4.048q.586-.586.586-1.414t-.587-1.413T12 12.539t-1.413.586T10 14.538t.587 1.414t1.413.586t1.414-.586M7.576 9.769h5.808q.348 0 .578-.23t.23-.577V7.577q0-.348-.23-.578t-.578-.23H7.577q-.348 0-.578.23t-.23.578v1.385q0 .348.23.578t.578.23");
}

</style>
