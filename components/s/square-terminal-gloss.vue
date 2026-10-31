<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw2f2mrxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw2f2mrxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-terminal-gloss" /></template>
