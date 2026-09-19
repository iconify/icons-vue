<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5xul3dgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d5xul3dgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-interface" /></template>
