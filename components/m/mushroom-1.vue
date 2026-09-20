<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4uxyb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="zb4uxyb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mushroom-1" /></template>
