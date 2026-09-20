<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d82qtqb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="d82qtqb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:unlink-vertical" /></template>
