<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh0v_w0pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wh0v_w0pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:signature" /></template>
