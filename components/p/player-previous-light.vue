<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1223mbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1223mbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-previous-light" /></template>
