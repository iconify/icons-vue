<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilr3y11pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilr3y11pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:team-upgrade" /></template>
