<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bt4xg4ftq.css';
import '../../css/h/h3lgm2bjn.css';
import '../../css/a/a0rpx6b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt4xg4ftq"/><path class="h3lgm2bjn"/><path class="a0rpx6b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wallet-01" /></template>
