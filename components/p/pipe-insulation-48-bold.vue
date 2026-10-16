<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0bb00b5y.css';
import '../../css/q/q5bh6acin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e0bb00b5y"/><path class="q5bh6acin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-insulation-48-bold" /></template>
