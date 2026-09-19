<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd6a6gjuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd6a6gjuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-frame" /></template>
