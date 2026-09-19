<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cslcpehvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cslcpehvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:roller-skate" /></template>
