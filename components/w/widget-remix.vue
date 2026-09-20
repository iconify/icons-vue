<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc1765b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qc1765b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:widget-remix" /></template>
