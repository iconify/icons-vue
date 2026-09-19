<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-4yw3brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-4yw3brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:radar-dish" /></template>
