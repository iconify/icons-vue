<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_e50nvyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j_e50nvyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-50" /></template>
