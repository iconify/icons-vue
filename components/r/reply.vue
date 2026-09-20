<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2l57cw4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x2l57cw4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:reply" /></template>
