<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfw21bb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfw21bb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underfloor-heating-48" /></template>
