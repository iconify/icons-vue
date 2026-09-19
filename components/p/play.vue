<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-072xbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t-072xbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:play" /></template>
