<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyqian0hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyqian0hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rss-round" /></template>
