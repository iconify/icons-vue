<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2jwnnbyn.css';
import '../../css/t/tqz5znvkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g2jwnnbyn"/><path class="tqz5znvkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:purple-heart" /></template>
