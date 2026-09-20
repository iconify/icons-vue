<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ylhfzzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:missed-video-call-outline-sharp" /></template>
<style>
.h9ylhfzzl {
  fill: currentColor;
  d: path("M3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19zm1-1h12V6h-12zm0 0V6zm6.74-2.692l3.807-3.858l-.708-.708l-3.1 3.139l-3.43-3.42h2.269v-1h-4v4h1v-2.315z");
}

</style>
