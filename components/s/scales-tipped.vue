<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uog2ysb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uog2ysb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scales-tipped" /></template>
