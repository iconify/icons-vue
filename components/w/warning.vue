<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sse8e8bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sse8e8bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:warning" /></template>
