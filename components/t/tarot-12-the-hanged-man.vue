<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdguj2hdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdguj2hdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-12-the-hanged-man" /></template>
