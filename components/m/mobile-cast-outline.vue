<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwpp9b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-cast-outline" /></template>
<style>
.rlwpp9b0w {
  fill: currentColor;
  d: path("M6 22v-1.384q.575 0 .98.404t.404.98zm3.77 0q0-1.573-1.099-2.671T6 18.23v-1q1.98 0 3.375 1.394T10.769 22zm3.384 0q0-2.984-2.085-5.07Q8.984 14.847 6 14.847v-1q1.69 0 3.179.643q1.488.644 2.588 1.744t1.743 2.588t.644 3.179zm4.923-18.384V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31V21q0 .402-.299.701q-.3.299-.701.299V3.616q0-.27-.173-.443T16.462 3H7.616q-.27 0-.443.173T7 3.616v7.845H6V3.617q0-.691.463-1.153T7.616 2h8.846q.69 0 1.153.463t.462 1.152m-5.49 2.473q.22-.22.22-.55q0-.329-.22-.549t-.548-.22q-.33 0-.55.22t-.22.55q0 .328.22.549q.22.22.55.22q.328 0 .549-.22M17.077 22V3z");
}

</style>
