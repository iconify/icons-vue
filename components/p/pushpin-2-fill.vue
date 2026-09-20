<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fahwwo24s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fahwwo24s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pushpin-2-fill" /></template>
