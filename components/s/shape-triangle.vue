<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u79ntacah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u79ntacah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:shape-triangle" /></template>
