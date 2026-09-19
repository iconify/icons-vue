<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9u4l7btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9u4l7btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:opening-shell" /></template>
