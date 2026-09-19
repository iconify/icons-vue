<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9k5d7bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9k5d7bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:office-chair" /></template>
