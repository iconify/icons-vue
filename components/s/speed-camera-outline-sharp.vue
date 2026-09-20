<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg3450iko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-camera-outline-sharp" /></template>
<style>
.qg3450iko {
  fill: currentColor;
  d: path("m17.467 14.27l-1.213-.693l2.558-1.87L20 12.4zm-4.013-1.609l3.292-2.397l-8.054-4.456l-1.884 3.177zM5 19v-1h4.808v-6.22l-4.38-2.436l2.866-4.857l10.27 5.692l-5.043 3.665l-2.733-1.503V19zm6.777-9.775");
}

</style>
