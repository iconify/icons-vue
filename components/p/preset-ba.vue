<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wae5ng5nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wae5ng5nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:preset-ba" /></template>
