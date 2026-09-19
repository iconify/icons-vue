<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxjvw-3ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yxjvw-3ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:north-wind-mahjong" /></template>
