<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw2a3ibob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nw2a3ibob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-operator" /></template>
