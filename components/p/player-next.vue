<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibuo_pw6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ibuo_pw6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:player-next" /></template>
