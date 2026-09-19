<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edd34ccwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="edd34ccwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:swot-filled" /></template>
