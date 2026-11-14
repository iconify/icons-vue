<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awqvw09ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stool" /></template>
<style>
.awqvw09ro {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 2.75H5.75q-1.036 0-1.768.732T3.25 5.25q0 2.5 2.5 2.5h.348L3.763 20.363q-.028.147.003.293t.116.269t.21.204t.271.108q.073.014.147.013t.146-.016t.14-.045q.068-.029.129-.071t.112-.095t.092-.115t.068-.13t.04-.141L7.624 7.75h3.626V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.75h3.626l2.387 12.887q.013.072.04.141t.068.13q.04.062.092.115q.051.053.112.095t.129.071t.14.045t.146.016q.074.001.147-.013q.072-.013.141-.04t.13-.068q.062-.04.115-.092q.053-.051.095-.112t.071-.129t.045-.14t.016-.146q.001-.074-.013-.147L17.902 7.75h.348q2.5 0 2.5-2.5q0-1.036-.732-1.768T18.25 2.75");
}

</style>
