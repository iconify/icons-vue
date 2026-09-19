<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7px1cbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7px1cbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sanitizer" /></template>
