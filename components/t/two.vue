<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8u14tbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8u14tbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:two" /></template>
