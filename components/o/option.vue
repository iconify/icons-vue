<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7j7_dq-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q7j7_dq-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:option" /></template>
