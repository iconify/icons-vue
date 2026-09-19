<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvt4d9b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wvt4d9b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sentiment-analysis" /></template>
