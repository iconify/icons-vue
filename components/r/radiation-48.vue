<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr4v5jaad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xr4v5jaad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-48" /></template>
