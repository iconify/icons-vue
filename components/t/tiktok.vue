<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhjytlb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rhjytlb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:tiktok" /></template>
