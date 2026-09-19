<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkd6icb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkd6icb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:refinery" /></template>
