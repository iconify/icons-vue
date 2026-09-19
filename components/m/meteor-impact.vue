<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a56ac9v7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a56ac9v7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meteor-impact" /></template>
