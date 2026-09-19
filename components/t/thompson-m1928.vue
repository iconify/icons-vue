<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7wwv7xym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7wwv7xym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thompson-m1928" /></template>
