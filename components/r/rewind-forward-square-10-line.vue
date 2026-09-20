<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzy-5qbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzy-5qbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-10-line" /></template>
