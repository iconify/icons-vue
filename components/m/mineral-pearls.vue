<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln91y3bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ln91y3bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mineral-pearls" /></template>
