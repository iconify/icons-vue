<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqsk4dbaf.css';
import '../../css/b/b8ymvlblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tqsk4dbaf"/><path class="b8ymvlblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-album-cd-disk-playlist" /></template>
