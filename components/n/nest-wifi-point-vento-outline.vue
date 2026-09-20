<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky9curjlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-wifi-point-vento-outline" /></template>
<style>
.ky9curjlp {
  fill: currentColor;
  d: path("M9 21q-2.5 0-4.25-1.75T3 15V9q0-2.5 1.75-4.25T9 3h6q2.5 0 4.25 1.75T21 9v6q0 2.5-1.75 4.25T15 21Zm-4-6h14V9q0-1.65-1.175-2.825Q16.65 5 15 5H9Q7.35 5 6.175 6.175Q5 7.35 5 9v6Zm4 4q0-.425.288-.712Q9.575 18 10 18t.713.288Q11 18.575 11 19h2q0-.425.288-.712Q13.575 18 14 18t.713.288Q15 18.575 15 19q1.125 0 2.025-.55q.9-.55 1.425-1.45H17q0 .425-.288.712Q16.425 18 16 18t-.712-.288Q15 17.425 15 17h-2q0 .425-.287.712Q12.425 18 12 18t-.712-.288Q11 17.425 11 17H9q0 .425-.287.712Q8.425 18 8 18t-.713-.288Q7 17.425 7 17H5.55q.525.9 1.425 1.45q.9.55 2.025.55Zm3-4Z");
}

</style>
