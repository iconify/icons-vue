<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otsa5xe7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otsa5xe7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unicycle" /></template>
