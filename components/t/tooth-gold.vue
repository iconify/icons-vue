<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aysbd0b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-gold" /></template>
<style>
.aysbd0b7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.275 7.193Q3.25 7.581 3.25 8q0 2.604 1.961 6.176q.381.694.574 1.071l.98 4.9q.308 1.541 1.735 1.541t1.735-1.541l.994-4.47q.054-.177.771-.177t.771.177l.997 4.486q.305 1.525 1.732 1.525t1.735-1.541l.98-4.9q.193-.377.574-1.071Q20.75 10.604 20.75 8q0-.419-.025-.807q-.016.059-.041.115t-.06.108t-.076.096t-.091.083q-.049.037-.103.066t-.113.049t-.119.03t-.122.01H4q-.034 0-.068-.003q-.148-.014-.281-.083q-.132-.069-.227-.184q-.106-.127-.149-.287");
}

</style>
