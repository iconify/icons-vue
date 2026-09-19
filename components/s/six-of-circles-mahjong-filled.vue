<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6imtiaxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j6imtiaxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:six-of-circles-mahjong-filled" /></template>
