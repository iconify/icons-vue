<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiimvjm9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iiimvjm9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:porcelain-vase" /></template>
