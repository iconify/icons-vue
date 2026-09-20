<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk_t0xb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk_t0xb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-centerline-dashed-vertical" /></template>
