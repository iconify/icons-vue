<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_h5xf82h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_h5xf82h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-half-line" /></template>
