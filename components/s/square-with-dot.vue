<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvh6w0bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cvh6w0bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-with-dot" /></template>
