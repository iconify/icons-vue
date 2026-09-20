<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy8c-45st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-convert" /></template>
<style>
.xy8c-45st {
  fill: currentColor;
  d: path("M12.5 14.885H20v3.5q0 .666-.475 1.14t-1.14.475H12.5zm0-1V8.769H20v5.116zM4 7.769V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615V7.77zM4 21v-1h2.704q-1.2-.46-1.966-1.532q-.767-1.072-.767-2.43q0-1.759 1.241-2.995q1.242-1.235 3.01-1.235v1q-1.356 0-2.304.944t-.947 2.308q0 1.157.725 2.046q.725.89 1.843 1.127v-2.771h1V21z");
}

</style>
