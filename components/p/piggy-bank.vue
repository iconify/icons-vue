<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1x5o90gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="q1x5o90gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:piggy-bank" /></template>
