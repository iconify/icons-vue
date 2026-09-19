<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kurhgmb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kurhgmb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steam-locomotive" /></template>
