<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5f0qtb6n.css';
import '../../css/y/yji6vpglu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w5f0qtb6n"/><path class="yji6vpglu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelchair-48-bold" /></template>
