<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng_19u0xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ng_19u0xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parallelogram-48" /></template>
