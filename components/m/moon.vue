<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqurnnynq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqurnnynq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:moon" /></template>
