<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99fn8lrk.css';
import '../../css/c/cna8fmbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t99fn8lrk"/><path class="cna8fmbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:teabag" /></template>
