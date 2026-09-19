<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdafhn1uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mdafhn1uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:west-wind-mahjong" /></template>
