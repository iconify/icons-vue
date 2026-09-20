<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qctbfml7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qctbfml7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:word-wrap-around-bounding-box-solid" /></template>
