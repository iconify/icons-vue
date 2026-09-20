<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjp-q-2bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="wjp-q-2bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pie-half" /></template>
