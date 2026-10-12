<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m61ifcb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m61ifcb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-root-48" /></template>
