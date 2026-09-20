<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa9p1mb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa9p1mb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:send-fill" /></template>
