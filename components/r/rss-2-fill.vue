<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebvkeu9cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebvkeu9cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rss-2-fill" /></template>
