<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvvtuibkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wvvtuibkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:star" /></template>
