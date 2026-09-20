<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6gu-qbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t6gu-qbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-bin-3-remix" /></template>
