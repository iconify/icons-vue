<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3j1uwd6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d3j1uwd6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-folder-family" /></template>
