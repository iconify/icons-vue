<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfyy1z9jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfyy1z9jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stroke-line-cap-butt" /></template>
