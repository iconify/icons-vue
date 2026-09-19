<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn0ezyjmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn0ezyjmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:quote-single-left" /></template>
