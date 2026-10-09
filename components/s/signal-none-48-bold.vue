<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn7333whg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qn7333whg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-none-48-bold" /></template>
