<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1p5ql74z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1p5ql74z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ushanka" /></template>
