<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz4--lb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nz4--lb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-48-bold" /></template>
