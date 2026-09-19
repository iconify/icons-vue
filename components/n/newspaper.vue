<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef2r0cbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ef2r0cbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:newspaper" /></template>
