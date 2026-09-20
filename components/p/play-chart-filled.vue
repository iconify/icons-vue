<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_90m36fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_90m36fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-chart-filled" /></template>
