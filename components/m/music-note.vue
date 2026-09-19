<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_yv-xuoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_yv-xuoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:music-note" /></template>
