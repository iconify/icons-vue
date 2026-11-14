<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ejkfnzbox"/><path class="jwr-gxb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-rideshare" /></template>
<style>
.ejkfnzbox {
  d: path("M12.137 21.387L12 21.5C9 19 3.5 15 3.5 11q0-.209.01-.417t.031-.416t.051-.414q.031-.206.072-.411q.041-.204.091-.407q.051-.202.112-.402q.06-.199.131-.396q.07-.196.15-.389t.169-.381q.089-.189.188-.373q.098-.184.205-.363q.108-.179.224-.352q.115-.173.24-.341q.124-.167.256-.329q.133-.161.273-.315q.14-.155.288-.303q.147-.147.302-.287q.154-.14.316-.272q.161-.133.329-.257q.167-.124.341-.24q.173-.116.352-.223q.179-.108.363-.206t.373-.187t.381-.169t.389-.15t.396-.131t.402-.111t.407-.092t.411-.071q.206-.031.414-.051q.208-.021.416-.031t.417-.01t.417.01t.416.031q.208.02.414.051t.411.071t.407.092t.402.111t.396.131t.389.15t.381.169q.189.089.373.187t.363.206t.352.223q.174.116.341.24t.329.257t.316.272q.155.14.302.287q.148.148.288.303q.14.154.273.315q.132.162.256.329q.125.168.24.341q.116.173.224.352q.107.179.205.363q.099.184.188.373q.089.188.169.381t.15.389q.071.197.131.396q.061.2.112.402q.05.203.091.407q.041.205.072.411t.051.414t.031.416t.01.417a5 5 0 0 1-.265 1.568");
}

.jwr-gxb5s {
  d: path("m9 10l1-2.75h4L15 10m-.8 3.5H7.5V10h9v2.9m-.75 8.1L21 15.75m-4 0h4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
