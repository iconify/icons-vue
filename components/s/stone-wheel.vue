<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnu1e1qxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnu1e1qxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-wheel" /></template>
