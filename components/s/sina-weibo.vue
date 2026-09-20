<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ttfmbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8ttfmbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sina-weibo" /></template>
