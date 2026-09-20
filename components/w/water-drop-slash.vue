<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygs_qq5iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygs_qq5iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:water-drop-slash" /></template>
