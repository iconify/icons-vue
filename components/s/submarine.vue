<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_vy435b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl_vy435b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:submarine" /></template>
