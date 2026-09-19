<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi7q1bdwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vi7q1bdwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half-2-outline" /></template>
