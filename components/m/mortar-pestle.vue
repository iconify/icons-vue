<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j60w0rb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j60w0rb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mortar-pestle" /></template>
