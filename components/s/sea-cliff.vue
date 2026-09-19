<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8uc9-brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8uc9-brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-cliff" /></template>
