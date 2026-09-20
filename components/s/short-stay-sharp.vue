<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhpw2vbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:short-stay-sharp" /></template>
<style>
.lhpw2vbip {
  fill: currentColor;
  d: path("M9.73 9q-.632 0-1.065-.434Q8.23 8.133 8.23 7.5t.434-1.066Q9.098 6 9.73 6t1.066.434t.434 1.066t-.434 1.066Q10.364 9 9.731 9m4.087 11.185Q12.5 18.869 12.5 17.003t1.316-3.185t3.181-1.318q1.867 0 3.185 1.316Q21.5 15.13 21.5 16.997t-1.315 3.185t-3.182 1.318t-3.185-1.315m4.857-.964l.546-.546l-1.836-1.829v-2.73h-.77v3.046zM4.231 21V3h11v7.364q-.281.055-.521.14q-.24.087-.48.19V4h-9v7h8.074v.216q-1.16.748-1.914 1.8q-.755 1.051-1.063 2.346h-.096V13.5h-1v2h-2v1h2v2h.954v-1.038q.057.97.382 1.87t.88 1.668z");
}

</style>
