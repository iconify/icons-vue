<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h27oz2bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h27oz2bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:schrodingers-cat-dead" /></template>
