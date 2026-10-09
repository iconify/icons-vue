<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl0qemc8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fl0qemc8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-dashed-48-bold" /></template>
