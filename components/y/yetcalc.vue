<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5n76ccuk"/><circle class="tcalpbcik"/><circle class="yaoxe9w4t"/><path class="o1w6e7bdc"/><path class="f6i_qk55j"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yetcalc" /></template>
<style>
.f6i_qk55j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.23 30.646v2.775c0 .925-.756 1.682-1.68 1.682s-1.683-.757-1.683-1.682v-2.775m10.57-1.431v5.046c0 .504.336.84.84.84h.253m-1.934-4.455h1.766m13.37-14.672c0 .924-.757 1.681-1.682 1.681s-1.682-.757-1.682-1.682V14.88c0-.925.757-1.681 1.682-1.681s1.682.756 1.682 1.681m0 2.774v-4.456m-4.625 3.616c-.253.504-.841.84-1.43.84a1.687 1.687 0 0 1-1.682-1.681V14.88c0-.925.757-1.682 1.682-1.682c.589 0 1.177.336 1.43.84m6.066-3.111v5.887c0 .504.336.84.84.84h.253m4.194-.84c-.253.504-.841.84-1.43.84a1.687 1.687 0 0 1-1.682-1.681V14.88c0-.925.757-1.682 1.682-1.682c.589 0 1.177.336 1.43.84");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.o1w6e7bdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.436 14.676h9m-9 0h9m-2.357 19.586c-.253.505-.841.841-1.43.841a1.687 1.687 0 0 1-1.682-1.682v-1.093c0-.925.757-1.682 1.682-1.682s1.682.757 1.682 1.682v.589h-3.364m-1.737.504v2.27c0 .926-.756 1.683-1.68 1.683c-.505 0-.926-.169-1.178-.505");
}

.tcalpbcik {
  cx: 14.936px;
  cy: 12.684px;
  r: 0.75px;
  fill: currentColor;
}

.yaoxe9w4t {
  cx: 14.936px;
  cy: 16.668px;
  r: 0.75px;
  fill: currentColor;
}

.z5n76ccuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37M5.5 24h37m-13.773 7.096h9m-9 3.982h9");
}

</style>
