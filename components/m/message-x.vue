<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcg5__wh.css';
import '../../css/x/x42zgxb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="x42zgxb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-x" /></template>
