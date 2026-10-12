<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isf4hnbqo.css';
import '../../css/w/wxo8ojinh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="isf4hnbqo"/><path class="wxo8ojinh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penguin-48-bold" /></template>
