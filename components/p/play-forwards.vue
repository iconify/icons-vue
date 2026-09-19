<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yinali4xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yinali4xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:play-forwards" /></template>
