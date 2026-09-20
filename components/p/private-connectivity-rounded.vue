<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex9arfbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:private-connectivity-rounded" /></template>
<style>
.ex9arfbyn {
  fill: currentColor;
  d: path("M7.916 16.413Q6.194 14.825 6.017 12.5H2.884q-.213 0-.356-.143q-.144-.143-.144-.357t.144-.357t.357-.143h3.132q.177-2.325 1.9-3.912Q9.638 6 12 6t4.084 1.588t1.899 3.912h3.132q.214 0 .357.143q.144.143.144.357t-.144.357t-.357.143h-3.132q-.177 2.325-1.9 3.913Q14.363 18 12 18t-4.084-1.588M10 15.27h4q.367 0 .626-.259q.259-.258.259-.625v-3q0-.368-.259-.626q-.259-.259-.626-.259h-.115v-.784q0-.818-.537-1.401T12 7.73q-.787 0-1.336.549t-.549 1.336v.884H10q-.367 0-.626.259q-.258.258-.258.625v3q0 .368.258.626q.259.26.626.26m2-1.674q-.287 0-.499-.212t-.213-.5t.213-.499t.499-.212t.499.212t.213.5t-.213.499t-.499.212M10.885 10.5v-.885q0-.463.326-.789T12 8.5t.79.326t.326.79v.884z");
}

</style>
