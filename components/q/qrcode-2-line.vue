<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae6vf0y8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae6vf0y8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-2-line" /></template>
