<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvf7gwbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvf7gwbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swipe-left-filled" /></template>
