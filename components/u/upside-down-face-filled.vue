<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq289ebot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hq289ebot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:upside-down-face-filled" /></template>
