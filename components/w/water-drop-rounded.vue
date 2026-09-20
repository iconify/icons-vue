<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te5gdrhhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-drop-rounded" /></template>
<style>
.te5gdrhhv {
  fill: currentColor;
  d: path("M6.999 18.938Q5 16.875 5 13.803q0-1.36.62-2.74q.619-1.38 1.547-2.648q.93-1.269 2.006-2.392q1.077-1.124 2-1.956q.18-.161.393-.249q.212-.087.434-.087t.434.087t.393.25q.923.83 2 1.955q1.077 1.123 2.006 2.391t1.548 2.649t.619 2.74q0 3.072-2.002 5.135Q14.994 21 11.996 21t-4.998-2.062m5.218-.246q.223-.025.35-.153q.125-.13.125-.311q0-.212-.144-.329q-.144-.116-.367-.091q-1.025.075-2.29-.64q-1.266-.714-1.566-2.39q-.05-.236-.166-.353q-.117-.117-.295-.117q-.197 0-.335.147t-.083.44q.387 2.082 1.923 2.98t2.848.817");
}

</style>
