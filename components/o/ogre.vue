<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khit851qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="khit851qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ogre" /></template>
