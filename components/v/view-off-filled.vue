<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi-gm2nxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hi-gm2nxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-off-filled" /></template>
