<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wih8tubvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wih8tubvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pinwheel-2-fill" /></template>
