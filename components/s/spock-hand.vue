<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpw-f0nxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cpw-f0nxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spock-hand" /></template>
