<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbcb5bc6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-basket-outline-rounded" /></template>
<style>
.dbcb5bc6f {
  fill: currentColor;
  d: path("M6.044 20q-.54 0-.978-.316q-.439-.317-.581-.851L2.28 11.025q-.106-.379.134-.702q.239-.323.643-.323H7.75l3.592-5.416q.125-.18.292-.267q.168-.086.38-.086t.378.096t.292.277L16.238 10h4.704q.404 0 .653.323q.25.323.124.702l-2.242 7.808q-.143.534-.58.85q-.44.317-.98.317zm-.082-1h12.077q.211 0 .365-.125t.211-.336L20.7 11H3.3l2.085 7.539q.057.211.211.336t.366.125m6.739-3.299Q13 15.402 13 15t-.299-.701T12 14t-.701.299T11 15t.299.701T12 16t.701-.299M8.964 10h6.067l-3.037-4.623zM12 15");
}

</style>
