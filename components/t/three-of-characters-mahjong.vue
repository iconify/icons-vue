<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hurs0qbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hurs0qbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-of-characters-mahjong" /></template>
