<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7zsbtb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7zsbtb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volcano-48" /></template>
