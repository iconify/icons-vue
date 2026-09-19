<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9mrjx-_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9mrjx-_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:samurai-helmet" /></template>
