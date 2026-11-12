<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f468imb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f468imb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-bing-dark" /></template>
