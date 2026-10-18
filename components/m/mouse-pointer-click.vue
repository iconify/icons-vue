<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s46w8jbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s46w8jbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-click" /></template>
