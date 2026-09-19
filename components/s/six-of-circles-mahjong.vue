<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp61wiopl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cp61wiopl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:six-of-circles-mahjong" /></template>
