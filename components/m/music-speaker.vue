<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bstajwh4p.css';
import '../../css/f/fbeehkbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bstajwh4p"/><path class="fbeehkbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-speaker" /></template>
