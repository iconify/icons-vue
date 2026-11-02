<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze1h-9r7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze1h-9r7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mushroom-line" /></template>
