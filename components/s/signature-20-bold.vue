<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqsb49kgr.css';
import '../../css/a/ahzc34b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lqsb49kgr"/><path class="ahzc34b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signature-20-bold" /></template>
