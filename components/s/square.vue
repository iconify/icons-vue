<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb8m3n93e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb8m3n93e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square" /></template>
