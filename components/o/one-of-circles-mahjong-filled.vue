<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z85e-1boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z85e-1boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:one-of-circles-mahjong-filled" /></template>
