<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiin5c7nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uiin5c7nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saucepan" /></template>
