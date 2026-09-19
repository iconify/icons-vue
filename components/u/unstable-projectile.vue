<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mal-u0bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mal-u0bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unstable-projectile" /></template>
