<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd0fiy1eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd0fiy1eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mpv" /></template>
