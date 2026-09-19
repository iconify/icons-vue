<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbkhvrnir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbkhvrnir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plate-claw" /></template>
