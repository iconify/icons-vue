<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw0zipber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mw0zipber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uv-index-48" /></template>
