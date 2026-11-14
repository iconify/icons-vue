<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hroo6cf6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pizza-slice" /></template>
<style>
.hroo6cf6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.04 17.164v-.001L4.974 9.748q-.924-1.687.055-3.342T7.933 4.75h8.134q1.924.001 2.904 1.656q.979 1.655.055 3.342l-4.066 7.416q-.961 1.752-2.96 1.752t-2.96-1.752M10 6.75Q7.75 6.75 7.75 9T10 11.25T12.25 9T10 6.75m1.75 4.75q0 2.25 2.25 2.25q.932 0 1.591-.659t.659-1.591t-.659-1.591T14 9.25q-2.25 0-2.25 2.25");
}

</style>
