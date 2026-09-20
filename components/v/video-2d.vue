<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya_hj3bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya_hj3bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-2d" /></template>
