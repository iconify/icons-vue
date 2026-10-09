<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zldktgsnj.css';
import '../../css/o/o2cku2b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zldktgsnj"/><path class="o2cku2b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:procurement-48" /></template>
