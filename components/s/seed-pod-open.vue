<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3_zqpbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seed-pod-open" /></template>
<style>
.y3_zqpbao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.239 5.726q-.431 7.889-4.587 11.555q-4.243 3.744-12.225 2.965q-.071-.006-.14-.027q-.068-.02-.132-.053q-.063-.033-.12-.077q-.056-.045-.103-.099t-.082-.116q-.036-.062-.059-.13q-.023-.067-.033-.138t-.007-.143q.392-8.034 4.597-11.744q4.116-3.632 11.751-3.008l1.258-2.097q.038-.063.088-.118t.108-.099q.06-.044.127-.075q.066-.032.138-.05t.146-.021t.146.007t.143.036t.133.063t.118.088t.099.109t.075.126t.05.138t.021.146q.004.073-.007.146t-.036.143t-.063.133zM15.75 6.5q-2.25 0-2.25 2.25T15.75 11T18 8.75T15.75 6.5m-6.5 6q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25m-2 1.5Q5 14 5 16.25t2.25 2.25t2.25-2.25T7.25 14");
}

</style>
