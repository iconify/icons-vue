<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3gl0gtcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e3gl0gtcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:task-list-edit-solid" /></template>
