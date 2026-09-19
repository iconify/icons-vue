<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmc_7kbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mmc_7kbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:photo-video" /></template>
