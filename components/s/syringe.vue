<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuh1g2ctr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuh1g2ctr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:syringe" /></template>
