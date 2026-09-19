<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8z1in5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8z1in5ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:posts" /></template>
