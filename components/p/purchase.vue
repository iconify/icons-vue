<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6sho1bhy.css';
import '../../css/l/lhu4h4qes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6sho1bhy"/><path class="lhu4h4qes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:purchase" /></template>
