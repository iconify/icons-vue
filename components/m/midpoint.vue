<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsky6xb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="vsky6xb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:midpoint" /></template>
