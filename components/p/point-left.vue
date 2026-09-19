<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvg_b900s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wvg_b900s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:point-left" /></template>
