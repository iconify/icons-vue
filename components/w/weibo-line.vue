<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzo0zlbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzo0zlbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weibo-line" /></template>
