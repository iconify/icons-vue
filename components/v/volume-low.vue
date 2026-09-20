<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9li6m6qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="v9li6m6qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:volume-low" /></template>
