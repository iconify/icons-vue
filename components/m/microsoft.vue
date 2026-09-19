<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-n7bi8nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-n7bi8nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:microsoft" /></template>
