<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq2i94jsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq2i94jsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wheel-barrow" /></template>
