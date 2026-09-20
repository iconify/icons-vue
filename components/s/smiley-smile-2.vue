<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huogh35_q.css';
import '../../css/d/d_3u0kb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huogh35_q"/><path class="d_3u0kb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-smile-2" /></template>
