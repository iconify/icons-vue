<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz6wm02jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bz6wm02jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:transform" /></template>
