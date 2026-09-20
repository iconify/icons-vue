<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrlu6h6mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrlu6h6mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:webcam-video" /></template>
