<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqv5e8bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqv5e8bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:smoking-orb" /></template>
