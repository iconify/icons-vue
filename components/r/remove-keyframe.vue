<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssj5qzlxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssj5qzlxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:remove-keyframe" /></template>
