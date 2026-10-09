<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxgwi8bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bxgwi8bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:octagon-48" /></template>
