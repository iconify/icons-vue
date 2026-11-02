<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utk78xbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utk78xbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:perplexity-line" /></template>
