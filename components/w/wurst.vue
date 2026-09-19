<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo-wl5pgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo-wl5pgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wurst" /></template>
