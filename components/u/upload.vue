<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei5vwb4va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ei5vwb4va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:upload" /></template>
