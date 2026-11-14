<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1kvb9aeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-overview" /></template>
<style>
.m1kvb9aeh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.859l4.25-1.771q.961-.401 1.922 0l4.655 1.94q.384.16.769 0l2.904-1.21q1.234-.515 2.348.227t1.113 2.08v10.708q.001 1.667-1.539 2.308l-4.25 1.771q-.961.401-1.922 0l-4.655-1.94q-.384-.16-.769 0l-2.904 1.21q-1.234.515-2.348-.227t-1.113-2.08V7.167Q2.249 5.5 3.789 4.859M15.25 9q0 .665.252 1.077q-1.188 1.326-3.452 1.175q-4.302-.287-5.75 3.479q-.027.069-.039.142t-.011.146q.002.074.018.146q.017.072.047.14q.03.067.072.127q.043.061.096.112t.116.09t.132.066q.139.054.288.05t.286-.065t.239-.168q.102-.109.156-.248q1.052-2.734 4.25-2.521q3.341.223 4.961-1.999l.089.001q1.75 0 1.75-1.75T17 7.25T15.25 9");
}

</style>
