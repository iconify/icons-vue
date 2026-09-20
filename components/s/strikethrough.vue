<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wao5n55nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wao5n55nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:strikethrough" /></template>
