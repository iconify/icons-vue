<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq9pr2-7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq9pr2-7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rune-sword" /></template>
