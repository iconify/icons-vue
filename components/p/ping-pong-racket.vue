<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlenh5bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="zlenh5bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ping-pong-racket" /></template>
