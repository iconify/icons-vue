<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m6t9d7bky"/><path class="ei3g7d_fk"/><path class="v8fzrboci"/><path class="ar9hbxyso"/><path class="lpm2e23zo"/><path class="km0rz_boi"/><path class="e_4yofwch"/><path class="jak-_uijv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-3-linear" /></template>
<style>
.ar9hbxyso {
  d: path("M2.00012 13.9999L4.2218 11.2928");
}

.e_4yofwch {
  stroke-linejoin: round;
  d: path("M9.17163 7.75684H9.17173");
}

.ei3g7d_fk {
  d: path("M3.636 20.364L7.75732 16.2427");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jak-_uijv {
  d: path("M11.8764 5.09345L11.8509 5.0783C9.22709 3.47503 6.85136 3.00679 5.75899 4.09916C4.12909 5.72907 5.97361 10.2162 9.87885 14.1214C13.7841 18.0267 18.2712 19.8712 19.9011 18.2413C20.9935 17.1489 20.5253 14.7732 18.922 12.1494L18.9083 12.1225");
}

.km0rz_boi {
  stroke-linejoin: round;
  d: path("M12 12H12.0001");
}

.lpm2e23zo {
  stroke-linejoin: round;
  d: path("M16.2427 14.8281H16.2428");
}

.m6t9d7bky {
  d: path("M14.1213 9.87866C16.3768 12.1342 17.5987 12.6043 18.0951 12.6934C18.2696 12.7248 18.4304 12.6406 18.5557 12.5153C20.4024 10.6686 20.4024 7.67451 18.5557 5.82781L18.1721 5.44423C16.3254 3.59753 13.3313 3.59753 11.4846 5.44423C11.3593 5.56956 11.2752 5.73033 11.3065 5.9048C11.3957 6.40126 11.8657 7.6231 14.1213 9.87866Z");
}

.v8fzrboci {
  d: path("M9.99988 21.9996L12.7072 19.7782");
}

</style>
