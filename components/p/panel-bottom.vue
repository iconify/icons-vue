<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqpl0teuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqpl0teuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:panel-bottom" /></template>
