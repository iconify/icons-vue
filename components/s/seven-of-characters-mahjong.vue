<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbqeu9bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zbqeu9bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:seven-of-characters-mahjong" /></template>
