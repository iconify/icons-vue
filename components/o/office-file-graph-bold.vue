<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_h32ggwa.css';
import '../../css/y/yka_8gutb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_h32ggwa"/><path class="yka_8gutb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-file-graph-bold" /></template>
