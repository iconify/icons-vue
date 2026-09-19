<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmh4bcbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmh4bcbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pawn" /></template>
