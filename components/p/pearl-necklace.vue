<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4vn-2u8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4vn-2u8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pearl-necklace" /></template>
