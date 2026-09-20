<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sltrw_bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sltrw_bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:suitcase-rolling-solid" /></template>
