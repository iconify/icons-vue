<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilai06dxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilai06dxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:squats-fill" /></template>
