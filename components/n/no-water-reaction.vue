<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av8fdc8um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:no-water-reaction" /></template>
<style>
.av8fdc8um {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 14.562V14.5C18.5 10 14 5 12 2.5c-.636.795-1.526 1.844-2.443 3.049m-3.066 4.924C5.89 11.808 5.5 13.176 5.5 14.5q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297q.061.148.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209q.124.101.252.196t.261.184t.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T12 21q.505 0 1.004-.078q.5-.078.981-.232t.932-.381t.863-.521M3.5 3.5l17 17");
}

</style>
