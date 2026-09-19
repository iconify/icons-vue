<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3wds3ztu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c3wds3ztu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:two-of-bamboos-mahjong-filled" /></template>
