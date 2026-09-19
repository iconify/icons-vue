<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1fwchzee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1fwchzee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soccer-kick" /></template>
