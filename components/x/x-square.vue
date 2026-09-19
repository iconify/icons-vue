<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en-_y_-fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en-_y_-fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:x-square" /></template>
