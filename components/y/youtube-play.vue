<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvk456bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="zvk456bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:youtube-play" /></template>
