<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-znqqq8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-znqqq8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:templar-heart" /></template>
