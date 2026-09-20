<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2gg18hzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2gg18hzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:trees-3" /></template>
