<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsydg8b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-ec-rounded" /></template>
<style>
.nsydg8b-p {
  fill: currentColor;
  d: path("M6.999 18.938Q5 16.875 5 13.803q0-1.36.62-2.74q.619-1.38 1.547-2.648q.93-1.269 2.006-2.392q1.077-1.124 2-1.956q.18-.161.393-.249q.212-.087.434-.087t.434.087t.393.25q.923.83 2 1.955q1.077 1.123 2.006 2.391t1.548 2.649t.619 2.74q0 3.072-2.002 5.135Q14.994 21 11.996 21t-4.998-2.062m4.501-5.246v3.658q0 .202.199.244t.284-.123l2.358-4.56q.117-.213-.011-.408t-.343-.195H12.5V8.65q0-.202-.199-.244t-.284.123l-2.358 4.56q-.117.213.011.408t.343.195z");
}

</style>
