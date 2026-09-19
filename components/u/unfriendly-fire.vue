<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiog0gj8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tiog0gj8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unfriendly-fire" /></template>
