<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7un97b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7un97b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:resting-vampire" /></template>
