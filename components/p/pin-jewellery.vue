<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7um3cbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-jewellery" /></template>
<style>
.j7um3cbjq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.46 4.11q-.224.372-.316.729q-.089.048-.163.118q-.073.071-.125.158t-.079.185t-.027.199q0 .062.01.123t.031.12q.02.059.049.113t.068.104t.083.091t.098.076q.052.034.108.059q.057.025.117.041q.176.324.484.631l1.575 1.575q-1.771.419-3.146 1.794Q5.25 12.204 5.25 15t1.977 4.773T12 21.75t4.773-1.977T18.75 15t-1.977-4.773q-1.375-1.375-3.146-1.794l1.576-1.575q.307-.308.483-.631q.06-.016.117-.041q.056-.025.108-.059t.098-.076t.083-.091q.038-.049.068-.104q.029-.054.05-.113q.02-.059.03-.12t.01-.123q0-.101-.027-.199t-.079-.185t-.125-.158t-.163-.118q-.092-.357-.316-.729l-.46-.769q-.655-1.092-1.929-1.092h-2.302q-1.274 0-1.929 1.093z");
}

</style>
