<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj7t-p0hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-feedback-score" /></template>
<style>
.jj7t-p0hn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25q-3.25 0-3.25 3.25v9q0 2.345 2 2.69v3.31q0 .138.049.267q.049.128.14.231q.1.112.234.177t.283.074t.29-.04t.252-.148l4.287-3.811H17.5q3.25 0 3.25-3.25V5.5q0-3.25-3.25-3.25zm6.845 3.907l.309.685q.176.39.601.437l.747.081q.947.106 1.241 1.011q.295.906-.409 1.547l-.557.506q-.316.288-.23.707l.153.735q.192.934-.578 1.493t-1.597.089l-.653-.372q-.372-.212-.744 0l-.653.372q-.827.47-1.597-.089t-.579-1.491l.154-.738q.086-.418-.23-.706l-.556-.505q-.705-.642-.41-1.548q.294-.905 1.24-1.01l.748-.083q.425-.046.601-.436l.309-.685q.394-.868 1.345-.868t1.344.866z");
}

</style>
