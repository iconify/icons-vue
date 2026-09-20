<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox3ovf3vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox3ovf3vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:undo-1" /></template>
