<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li9ny1yau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-basket-rounded" /></template>
<style>
.li9ny1yau {
  fill: currentColor;
  d: path("M6.044 20q-.54 0-.978-.316q-.439-.317-.581-.851L2.28 11.025q-.106-.379.134-.702q.239-.323.643-.323H7.75l3.862-5.82q.067-.103.176-.16q.11-.059.225-.059q.116 0 .225.058q.11.058.177.162L16.238 10h4.704q.404 0 .653.323q.25.323.124.702l-2.242 7.808q-.143.534-.58.85q-.44.317-.98.317zm6.657-4.299Q13 15.402 13 15t-.299-.701T12 14t-.701.299T11 15t.299.701T12 16t.701-.299M8.964 10h6.067l-3.037-4.623z");
}

</style>
