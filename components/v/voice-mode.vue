<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbfb1bccc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wbfb1bccc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:voice-mode" /></template>
