<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vext9xb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vext9xb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-altar" /></template>
