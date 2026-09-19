<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jit-jvg3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jit-jvg3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-left-06" /></template>
