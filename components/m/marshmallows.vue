<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxete_bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxete_bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:marshmallows" /></template>
