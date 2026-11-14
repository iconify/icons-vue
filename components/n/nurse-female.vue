<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rix_1hbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nurse-female" /></template>
<style>
.rix_1hbqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.272 5.318l.75-3q.016-.06.04-.117q.025-.058.059-.11t.076-.098t.091-.084t.104-.068t.114-.05t.12-.031t.124-.01h6.5q.062 0 .124.01q.061.011.12.031t.114.05q.054.03.104.068t.091.084t.076.098t.059.11t.04.117l.75 3q.023.094.022.191t-.027.191t-.075.177q-.048.084-.117.153q.219.689.219 1.47q0 .343-.042.669q1.439 2.808.49 6.705q.473.241.909.535Q20.75 17.191 20.75 20q0 1.75-1.75 1.75H5q-1.75 0-1.75-1.75q0-2.809 2.643-4.591q.436-.294.909-.535q-.949-3.897.49-6.705q-.042-.326-.042-.669q0-.781.219-1.47q-.069-.069-.117-.153q-.049-.084-.075-.177q-.026-.094-.027-.191t.022-.191m8.52 8.978q.511-2.264.09-4.047q-.231.318-.523.61Q13.968 12.25 12 12.25t-3.359-1.391q-.292-.292-.523-.61q-.421 1.783.09 4.047Q9.909 13.75 12 13.75t3.792.546");
}

</style>
