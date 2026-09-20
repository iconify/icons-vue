<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guq7n-k9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-highlighter" /></template>
<style>
.guq7n-k9s {
  fill: currentColor;
  d: path("M7.673 15.308V5.616q0-.672.472-1.144T9.29 4q.186 0 .363.04t.339.121l5.403 2.649q.423.211.669.603t.245.85v7.045zM5 20l.473-1.317q.162-.452.533-.722t.848-.269h10.292q.477 0 .848.27t.533.72L19 20z");
}

</style>
