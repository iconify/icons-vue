<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi2d1hbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi2d1hbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tv-2-line" /></template>
