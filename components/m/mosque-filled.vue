<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-7w5gbig.css';
import '../../css/y/y1hb6nbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-7w5gbig"/><path class="y1hb6nbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mosque-filled" /></template>
