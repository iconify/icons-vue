<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt1wq7lox.css';
import '../../css/k/kabj7mbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt1wq7lox"/><path class="kabj7mbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sale-line" /></template>
