<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrz70jbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrz70jbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:monument-line" /></template>
