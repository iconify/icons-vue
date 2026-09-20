<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koyp5ltmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="koyp5ltmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:yin-yang-symbol-remix" /></template>
