<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz9gp_bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oz9gp_bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rolling-dice-cup" /></template>
