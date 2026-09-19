<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5wxgb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ci5wxgb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-forked-compact" /></template>
