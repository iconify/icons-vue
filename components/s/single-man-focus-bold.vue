<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atr8lybzg.css';
import '../../css/q/qbrel2bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atr8lybzg"/><path class="qbrel2bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-man-focus-bold" /></template>
