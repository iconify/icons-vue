<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-p_6nalg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-p_6nalg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-medal" /></template>
