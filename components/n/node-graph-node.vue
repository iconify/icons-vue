<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl2a4taoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nl2a4taoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:node-graph-node" /></template>
