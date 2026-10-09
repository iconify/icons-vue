<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8j44qm-v.css';
import '../../css/q/q7zl1sbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d8j44qm-v"/><path class="q7zl1sbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rivet-48-bold" /></template>
