<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmv-ntbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qmv-ntbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:steps-1-remix" /></template>
