<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugpvx7r2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milestone-remove" /></template>
<style>
.ugpvx7r2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.898 14.58q-.107.08-.227.14t-.249.098t-.262.052t-.268.005q-.133-.01-.263-.043t-.253-.089t-.232-.132q-.11-.077-.205-.172l-3.878-3.878q-.052-.052-.099-.109t-.088-.118t-.075-.127q-.035-.065-.063-.133q-.029-.068-.05-.138t-.036-.143t-.021-.146q-.008-.073-.008-.147t.008-.147t.021-.146q.015-.072.036-.143t.05-.138q.028-.068.063-.133q.034-.065.075-.127q.041-.061.088-.118t.099-.109l3.878-3.878q.052-.052.109-.099t.118-.088t.127-.075q.065-.035.133-.063q.068-.029.138-.05t.143-.036t.146-.021q.073-.008.147-.008t.147.008t.146.021q.072.015.143.036t.138.05q.068.028.133.063q.065.034.127.075q.061.041.118.088t.109.099l3.878 3.878q.052.052.099.109t.088.118t.075.127q.035.065.063.133q.029.068.05.138t.036.143q.014.073.021.146t.008.147t-.008.147q-.007.073-.021.146q-.015.072-.036.143t-.05.138q-.028.068-.063.133q-.034.065-.075.127q-.041.061-.088.118t-.099.109L14.61 12.89M2.5 9.5H6m12 0h3.5m-6 6l5 5m0-5l-5 5");
}

</style>
