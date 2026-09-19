<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx-7mnbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-7mnbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:movie-play" /></template>
