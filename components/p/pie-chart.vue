<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3zl73i7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k3zl73i7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pie-chart" /></template>
