<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rex-s-bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rex-s-bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:reactor" /></template>
