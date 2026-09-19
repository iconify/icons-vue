<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4d_zkbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4d_zkbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:olive" /></template>
