<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jxoqb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surgical-scissors" /></template>
<style>
.n7jxoqb5e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.432 16.248Q10 17.09 10 18.5Q10 22 6.5 22T3 18.5T6.5 15q1.035 0 1.764.306l2.763-3.341l-6.605-7.987q-.047-.057-.082-.122t-.057-.136t-.029-.144t-.001-.147t.028-.144t.056-.136q.035-.065.081-.123q.047-.057.104-.104t.122-.082t.136-.057q.07-.022.144-.029t.147-.001t.144.028t.136.056t.123.081t.104.104L12 10.788l6.422-7.766q.047-.057.104-.104q.058-.046.123-.081q.065-.034.136-.056t.144-.028q.074-.007.147.001q.074.007.144.029q.071.022.136.057t.122.082q.115.095.185.227t.084.28t-.03.291t-.139.258l-6.605 7.987l2.763 3.341Q16.465 15 17.5 15q3.5 0 3.5 3.5T17.5 22T14 18.5q0-1.41.568-2.252L12 13.142z");
}

</style>
