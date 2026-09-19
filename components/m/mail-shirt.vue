<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di2srog2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di2srog2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mail-shirt" /></template>
