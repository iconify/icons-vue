<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7pu0ex4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7pu0ex4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:split-square-vertical" /></template>
