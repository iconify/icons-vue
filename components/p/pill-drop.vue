<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx62a9nxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx62a9nxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pill-drop" /></template>
