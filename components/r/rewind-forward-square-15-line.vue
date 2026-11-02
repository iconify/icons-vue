<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhgvhrlrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhgvhrlrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-15-line" /></template>
