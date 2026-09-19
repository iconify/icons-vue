<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erfm81btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erfm81btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tiger" /></template>
