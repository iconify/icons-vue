<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp4o9et5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp4o9et5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:windmill-off" /></template>
