<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvr9ptb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-outline-sharp" /></template>
<style>
.hvr9ptb_g {
  fill: currentColor;
  d: path("M19 22H5V2h14zm-2-2V4H7v16zM13.413 8.413Q14 7.825 14 7t-.587-1.412T12 5t-1.412.588T10 7t.588 1.413T12 9t1.413-.587m1.412 9.412Q16 16.65 16 15t-1.175-2.825T12 11t-2.825 1.175T8 15t1.175 2.825T12 19t2.825-1.175m-4.237-1.412Q10 15.824 10 15t.588-1.412T12 13t1.413.588T14 15t-.587 1.413T12 17t-1.412-.587M7 4v16z");
}

</style>
