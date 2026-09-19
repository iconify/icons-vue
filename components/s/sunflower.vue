<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjrggn2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzjrggn2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunflower" /></template>
