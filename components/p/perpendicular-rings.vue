<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp2m1wbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pp2m1wbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perpendicular-rings" /></template>
