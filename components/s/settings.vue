<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyi21vbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vyi21vbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:settings" /></template>
