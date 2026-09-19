<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkhvx13gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkhvx13gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:return-arrow" /></template>
