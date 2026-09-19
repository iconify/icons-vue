<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxvm15b7r.css';
import '../../css/j/jq2vx7i2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xxvm15b7r"/><path class="jq2vx7i2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:word-cloud" /></template>
