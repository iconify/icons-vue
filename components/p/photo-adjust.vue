<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7wdoxb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:photo-adjust" /></template>
<style>
.k7wdoxb-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h9.25q2.123 0 3.624 1.501t1.501 3.624v5.997Q19.857 12.75 18 12.75q-2.175 0-3.712 1.538q-1.022 1.021-1.365 2.323L9.58 12.525q-.047-.058-.105-.105t-.122-.082q-.066-.035-.136-.056t-.145-.028q-.073-.008-.147 0q-.073.007-.144.029q-.07.021-.136.056q-.065.035-.122.082t-.103.104l-4.5 5.5q-.077.094-.12.207q-.284-.218-.549-.483q-1.501-1.501-1.501-3.624v-6.25q0-2.123 1.501-3.624T6.875 2.75M12 8.5q0 2.5 2.5 2.5q1.036 0 1.768-.732T17 8.5t-.732-1.768T14.5 6Q12 6 12 8.5m6 5.5q-4 0-4 4t4 4t4-4t-4-4m-5.189 4.843q.031.207.078.407H6.875q-.949 0-1.774-.3L9 14.184zM15.5 18q0-2.092 1.75-2.433v4.866Q15.5 20.092 15.5 18m5 0q0 2.092-1.75 2.433v-4.866q1.75.341 1.75 2.433");
}

</style>
