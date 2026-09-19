<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2h36m46b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2h36m46b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saber-and-pistol" /></template>
