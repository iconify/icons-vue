<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp3lsl9jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp3lsl9jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-3-line" /></template>
