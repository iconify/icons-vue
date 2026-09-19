<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe4t69j8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oe4t69j8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-method" /></template>
