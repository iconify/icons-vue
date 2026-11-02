<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylhe3bqrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylhe3bqrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:swimming-line" /></template>
