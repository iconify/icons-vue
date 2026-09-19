<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qopto-x0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qopto-x0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-fill-16" /></template>
