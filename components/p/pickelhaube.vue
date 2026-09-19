<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0h8_ovwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0h8_ovwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pickelhaube" /></template>
