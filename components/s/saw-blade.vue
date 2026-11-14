<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="edrr_va0j"/><path class="rq_kn7bnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:saw-blade" /></template>
<style>
.edrr_va0j {
  d: path("m12.862 3.472l.151.17a1.5 1.5 0 0 0 1.701.388l.209-.087a1.153 1.153 0 0 1 1.554.748l.062.218a1.5 1.5 0 0 0 1.364 1.088l.227.012a1.153 1.153 0 0 1 1.075 1.348l-.039.223a1.5 1.5 0 0 0 .757 1.573l.199.109a1.153 1.153 0 0 1 .384 1.681l-.132.184a1.5 1.5 0 0 0 0 1.746l.132.184a1.153 1.153 0 0 1-.384 1.681l-.199.109a1.5 1.5 0 0 0-.757 1.573l.039.223a1.153 1.153 0 0 1-1.075 1.348l-.227.012a1.5 1.5 0 0 0-1.364 1.088l-.062.218a1.153 1.153 0 0 1-1.554.748l-.209-.087a1.5 1.5 0 0 0-1.701.388l-.151.17a1.153 1.153 0 0 1-1.724 0l-.151-.17a1.5 1.5 0 0 0-1.701-.388l-.209.087a1.153 1.153 0 0 1-1.554-.748l-.062-.218a1.5 1.5 0 0 0-1.364-1.088l-.227-.012a1.153 1.153 0 0 1-1.075-1.348l.039-.223a1.5 1.5 0 0 0-.757-1.573l-.199-.109a1.153 1.153 0 0 1-.384-1.681l.132-.184a1.5 1.5 0 0 0 0-1.746l-.132-.184a1.153 1.153 0 0 1 .384-1.681l.199-.109a1.5 1.5 0 0 0 .757-1.573l-.039-.223A1.153 1.153 0 0 1 5.87 6.009l.227-.012a1.5 1.5 0 0 0 1.364-1.088l.062-.218a1.153 1.153 0 0 1 1.554-.748l.209.087a1.5 1.5 0 0 0 1.701-.388l.151-.17a1.153 1.153 0 0 1 1.724 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rq_kn7bnn {
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
