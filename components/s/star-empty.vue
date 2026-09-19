<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpscodpek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qpscodpek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:star-empty" /></template>
