<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfuqf0bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfuqf0bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:webcam-gloss" /></template>
