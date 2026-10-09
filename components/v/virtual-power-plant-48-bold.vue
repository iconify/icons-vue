<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_ctiwi9q.css';
import '../../css/y/y_finwbhi.css';
import '../../css/l/lzsp7m9hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_ctiwi9q"/><path class="y_finwbhi"/><path class="lzsp7m9hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:virtual-power-plant-48-bold" /></template>
