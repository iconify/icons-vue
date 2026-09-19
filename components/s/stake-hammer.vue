<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edzzb9bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edzzb9bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stake-hammer" /></template>
