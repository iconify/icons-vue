<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrvyhh4xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sql-outline" /></template>
<style>
.hrvyhh4xy {
  fill: currentColor;
  d: path("M4.308 14.692q-.31 0-.501-.191T3.616 14v-.692H4.5v.5h2.616v-1.423H4.308q-.31 0-.501-.192t-.191-.5V10q0-.31.19-.501q.192-.191.502-.191h3q.31 0 .5.191Q8 9.69 8 10v.692h-.885v-.5H4.5v1.424h2.808q.31 0 .5.19q.192.192.192.502V14q0 .31-.191.501q-.192.191-.501.191zm7.827 1.5v-1.5h-.673q-.445 0-.761-.316t-.316-.76v-3.231q0-.444.316-.761q.316-.316.76-.316h2.231q.444 0 .761.316q.316.317.316.76v3.232q0 .444-.316.76t-.76.316h-.674v1.5zm-.558-2.384h2q.115 0 .212-.096t.096-.212v-3q0-.115-.096-.212q-.097-.096-.212-.096h-2q-.115 0-.211.096q-.097.096-.097.212v3q0 .116.097.212q.096.096.211.096m5.577-4.5h.885v4.5h2.346v.884h-3.231z");
}

</style>
