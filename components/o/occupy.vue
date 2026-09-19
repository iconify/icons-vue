<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro2c__2kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ro2c__2kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:occupy" /></template>
