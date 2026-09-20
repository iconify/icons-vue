<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0fqr5u6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-audio-call" /></template>
<style>
.y0fqr5u6q {
  fill: currentColor;
  d: path("M6 16q-.825 0-1.412-.588Q4 14.825 4 14v-4q0-.825.588-1.413Q5.175 8 6 8t1.412.587Q8 9.175 8 10v4q0 .825-.588 1.412Q6.825 16 6 16Zm12 0q-.825 0-1.413-.588Q16 14.825 16 14v-4q0-.825.587-1.413Q17.175 8 18 8q.825 0 1.413.587Q20 9.175 20 10v4q0 .825-.587 1.412Q18.825 16 18 16Zm-6 4q-.825 0-1.412-.587Q10 18.825 10 18V6q0-.825.588-1.412Q11.175 4 12 4t1.413.588Q14 5.175 14 6v12q0 .825-.587 1.413Q12.825 20 12 20Z");
}

</style>
