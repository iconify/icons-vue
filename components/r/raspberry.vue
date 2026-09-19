<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4akjb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kf4akjb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:raspberry" /></template>
