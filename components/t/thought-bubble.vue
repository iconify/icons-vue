<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl1dj3b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl1dj3b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thought-bubble" /></template>
