<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xudbvccqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xudbvccqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-beam" /></template>
