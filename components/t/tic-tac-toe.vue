<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn6qiobpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rn6qiobpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tic-tac-toe" /></template>
