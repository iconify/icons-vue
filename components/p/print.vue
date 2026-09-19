<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsu61nbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsu61nbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:print" /></template>
