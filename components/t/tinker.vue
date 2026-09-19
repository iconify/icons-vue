<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6t53cwua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k6t53cwua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tinker" /></template>
