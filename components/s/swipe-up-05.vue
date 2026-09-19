<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4cnv59j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv4cnv59j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-up-05" /></template>
