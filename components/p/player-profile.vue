<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2f-srbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:player-profile" /></template>
<style>
.o2f-srbeo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 1.75h8q1.76 0 3.005 1.245T20.25 6v12q0 1.76-1.245 3.005q-.943.943-2.182 1.172q.096-.046.175-.116q.08-.071.136-.161t.087-.192q.029-.102.029-.208q0-7-5.25-7t-5.25 7q0 .106.029.208t.087.192q.056.09.136.161q.079.07.175.116q-1.239-.229-2.182-1.172Q3.75 19.76 3.75 18V6q0-1.76 1.245-3.005T8 1.75m-.359 20.487q.177.013.359.013h8q.182 0 .359-.013q-.064-.013-.124-.036q-.061-.023-.117-.056t-.105-.075q-.05-.042-.091-.092t-.074-.107q-.032-.056-.054-.117t-.033-.125t-.011-.129q0-5.5-3.75-5.5t-3.75 5.5q0 .065-.011.129t-.033.125t-.054.117t-.074.107t-.091.092t-.105.075t-.117.056q-.06.023-.124.036M12 5Q8 5 8 9t4 4t4-4q0-1.657-1.172-2.828Q13.657 5 12 5");
}

</style>
