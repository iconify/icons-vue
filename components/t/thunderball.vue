<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrkgf0jsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrkgf0jsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thunderball" /></template>
