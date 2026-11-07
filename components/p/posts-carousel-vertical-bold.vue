<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcxpyny9b.css';
import '../../css/t/tslomuedm.css';
import '../../css/y/yjypexard.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcxpyny9b"/><path class="tslomuedm"/><path class="yjypexard"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-bold" /></template>
