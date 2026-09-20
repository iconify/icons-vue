<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqk1_ubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nightlife-sharp" /></template>
<style>
.kqk1_ubtd {
  fill: currentColor;
  d: path("M4.885 19.5v-1h2v-5.346L2.115 6h10.539l-4.77 7.154V18.5h2v1zm.4-10.5h4.2l1.361-2H3.923zm8.33 9.772q-.73-.729-.73-1.77t.729-1.771t1.77-.731q.399 0 .76.134q.362.133.74.45V6h4v1.77h-3V17q0 1.042-.728 1.77q-.728.73-1.769.73t-1.771-.728");
}

</style>
