<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6memojec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6memojec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-03-the-empress" /></template>
