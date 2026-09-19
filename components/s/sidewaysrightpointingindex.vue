<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl161n-1i.css';
import '../../css/f/fgm3acnse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cl161n-1i"/><path class="fgm3acnse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysrightpointingindex" /></template>
