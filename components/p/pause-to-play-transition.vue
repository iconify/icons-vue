<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb4hln.css';
import '../../css/d/d-d0cg1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb4hln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pause-to-play-transition" /></template>
