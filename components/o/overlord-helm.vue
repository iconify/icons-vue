<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wos7l5pvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wos7l5pvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:overlord-helm" /></template>
