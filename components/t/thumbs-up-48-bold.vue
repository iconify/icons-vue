<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3x9rfeak.css';
import '../../css/e/ebzb5lb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3x9rfeak"/><path class="ebzb5lb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-up-48-bold" /></template>
