<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taq8lbfgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="taq8lbfgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sankey-diagram-alt" /></template>
