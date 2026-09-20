<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i61u-tbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i61u-tbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:warning-diamond-remix" /></template>
