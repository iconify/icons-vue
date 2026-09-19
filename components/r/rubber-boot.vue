<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps048zbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ps048zbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rubber-boot" /></template>
