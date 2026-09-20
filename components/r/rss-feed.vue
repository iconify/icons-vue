<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j301gnb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="j301gnb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:rss-feed" /></template>
