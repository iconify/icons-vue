<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzjtm5bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzjtm5bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striking-diamonds" /></template>
