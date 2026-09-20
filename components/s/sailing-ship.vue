<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8c5so3vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j8c5so3vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sailing-ship" /></template>
