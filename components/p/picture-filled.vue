<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg5af8b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zg5af8b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:picture-filled" /></template>
