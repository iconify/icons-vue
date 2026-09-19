<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c984stk_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="c984stk_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pause" /></template>
