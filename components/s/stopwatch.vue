<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uarenacrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uarenacrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stopwatch" /></template>
