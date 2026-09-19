<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rawcm4w7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rawcm4w7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:stack" /></template>
