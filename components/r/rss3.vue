<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjv6_i5tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjv6_i5tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rss3" /></template>
