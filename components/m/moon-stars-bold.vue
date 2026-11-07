<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65hvpbwb.css';
import '../../css/t/t7fjfmboq.css';
import '../../css/z/zgg5gabcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g65hvpbwb"/><path class="t7fjfmboq"/><path class="zgg5gabcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-stars-bold" /></template>
