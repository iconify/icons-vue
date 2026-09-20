<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjb7rdlib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjb7rdlib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-upvote-dark" /></template>
