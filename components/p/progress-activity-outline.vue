<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="belfw4dms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:progress-activity-outline" /></template>
<style>
.belfw4dms {
  fill: currentColor;
  d: path("M8.503 20.293q-1.64-.708-2.864-1.932t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.864-1.93Q10.151 3 12 3q.213 0 .356.144t.144.357t-.144.356T12 4Q8.675 4 6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337T20 12q0-.213.144-.357t.357-.143t.356.144T21 12q0 1.85-.71 3.496q-.711 1.646-1.93 2.865t-2.855 1.929t-3.5.71t-3.502-.707");
}

</style>
