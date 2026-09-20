<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzebkbcpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qzebkbcpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:warranty-badge-highlight-remix" /></template>
