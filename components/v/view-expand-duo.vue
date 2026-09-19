<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3lgsmb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s3lgsmb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:view-expand-duo" /></template>
