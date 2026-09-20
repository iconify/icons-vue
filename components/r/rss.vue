<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj1vbobrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="uj1vbobrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rss" /></template>
