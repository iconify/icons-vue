<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdtwck09f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kdtwck09f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metal-skirt" /></template>
