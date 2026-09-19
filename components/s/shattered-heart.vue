<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkbevu3jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xkbevu3jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shattered-heart" /></template>
