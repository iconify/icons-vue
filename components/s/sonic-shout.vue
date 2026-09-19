<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v62n5nbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v62n5nbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sonic-shout" /></template>
