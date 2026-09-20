<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-lwfi6-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-lwfi6-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-graph-2" /></template>
