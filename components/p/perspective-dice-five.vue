<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6d77db6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6d77db6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-five" /></template>
