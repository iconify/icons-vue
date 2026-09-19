<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swg-av1ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swg-av1ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shadow-follower" /></template>
