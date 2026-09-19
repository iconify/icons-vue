<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klsy0h-si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klsy0h-si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:party-flags" /></template>
