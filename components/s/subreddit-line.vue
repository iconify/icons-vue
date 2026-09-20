<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8j5efbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8j5efbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:subreddit-line" /></template>
