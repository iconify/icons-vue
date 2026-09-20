<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3v5i-ofx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-edit-outline" /></template>
<style>
.l3v5i-ofx {
  fill: currentColor;
  d: path("M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.675 0 1.354.084t1.367.238l-.829.834q-.485-.066-.946-.111q-.46-.044-.946-.044q-1.335 0-2.646.318t-2.546.916q-.38.202-.593.494Q6 16.637 6 16.97v.647h5.846v1zM14.23 20v-2.21l5.334-5.307q.148-.148.305-.2q.158-.052.315-.052q.172 0 .338.064q.166.065.301.194l.925.944q.123.148.188.308q.064.159.064.319t-.061.322t-.191.31L16.44 20zm6.886-5.94l-.925-.945zm-6 5.056h.95l3.467-3.474l-.47-.475l-.455-.488l-3.492 3.487zm3.948-3.949l-.456-.488l.925.963zm-9.187-4.66Q9 9.632 9 8.386t.877-2.123T12 5.386t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588M12 8.385");
}

</style>
