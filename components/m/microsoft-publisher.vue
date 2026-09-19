<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvn7ycb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvn7ycb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-publisher" /></template>
