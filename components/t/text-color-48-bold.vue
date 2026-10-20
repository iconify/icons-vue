<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzbcp5bsh.css';
import '../../css/l/lu7edcbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rzbcp5bsh"/><path class="lu7edcbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-color-48-bold" /></template>
