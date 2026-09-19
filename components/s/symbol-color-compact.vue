<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-6urxbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p-6urxbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-color-compact" /></template>
