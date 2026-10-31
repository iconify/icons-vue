<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg5o3i7gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zg5o3i7gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tabletop-microphone-under-gabled-roof" /></template>
