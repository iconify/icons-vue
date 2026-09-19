<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fscw49xbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fscw49xbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nest-birds" /></template>
