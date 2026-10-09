<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9t92f57g.css';
import '../../css/c/c81pk53il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9t92f57g"/><path class="c81pk53il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:supply-chain-48-bold" /></template>
