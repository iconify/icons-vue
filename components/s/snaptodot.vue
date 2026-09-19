<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq6p5-u8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zq6p5-u8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:snaptodot" /></template>
