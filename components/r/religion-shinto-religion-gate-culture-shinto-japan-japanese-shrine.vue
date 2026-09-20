<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfeezi7xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cfeezi7xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:religion-shinto-religion-gate-culture-shinto-japan-japanese-shrine" /></template>
