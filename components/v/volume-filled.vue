<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnd-sxdgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnd-sxdgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volume-filled" /></template>
