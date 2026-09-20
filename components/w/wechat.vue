<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwvg8jbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwvg8jbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wechat" /></template>
