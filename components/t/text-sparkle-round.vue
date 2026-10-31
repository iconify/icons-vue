<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoebwfbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoebwfbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-sparkle-round" /></template>
