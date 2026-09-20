<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrsjxybtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":260};
const content = `<path class="qrsjxybtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openai-light" /></template>
