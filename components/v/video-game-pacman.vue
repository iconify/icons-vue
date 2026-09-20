<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3tro_brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3tro_brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:video-game-pacman" /></template>
