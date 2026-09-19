<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttbe-fbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ttbe-fbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:power-button" /></template>
