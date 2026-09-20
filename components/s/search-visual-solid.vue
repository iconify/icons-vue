<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ql1vbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4ql1vbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:search-visual-solid" /></template>
