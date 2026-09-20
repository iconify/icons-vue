<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd-v0buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="mpd-v0buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:replit" /></template>
