<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no5sv1bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no5sv1bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:winchester-rifle" /></template>
