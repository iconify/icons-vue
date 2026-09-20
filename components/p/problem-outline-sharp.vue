<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3umzijvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:problem-outline-sharp" /></template>
<style>
.u3umzijvy {
  fill: currentColor;
  d: path("M7.549 15.932q.22-.221.22-.549t-.221-.547t-.55-.22t-.547.221t-.22.549t.221.548t.55.22t.547-.222M6.5 13.231h1V7.846h-1zm4 1.269h7v-1h-7zm0-4h7v-1h-7zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
