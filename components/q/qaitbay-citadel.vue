<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr18i9bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nr18i9bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:qaitbay-citadel" /></template>
