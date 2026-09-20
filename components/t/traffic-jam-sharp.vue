<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oey8_3b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:traffic-jam-sharp" /></template>
<style>
.oey8_3b8j {
  fill: currentColor;
  d: path("M4 22H1v-9l2.5-6h11l2.5 6v9h-3v-2H4zm-.2-11h10.375l-.825-2h-8.7zm2.763 5.563Q7 16.125 7 15.5t-.437-1.062T5.5 14t-1.062.438T4 15.5t.438 1.063T5.5 17t1.063-.437m7 0Q14 16.125 14 15.5t-.437-1.062T12.5 14t-1.062.438T11 15.5t.438 1.063T12.5 17t1.063-.437M18 19v-8.6L16.175 6h-10.5L6.5 4h11l2.5 6v9zm3-3V7.4L19.175 3h-10.5L9.5 1h11L23 7v9z");
}

</style>
