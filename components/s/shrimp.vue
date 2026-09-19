<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s82z5ebmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s82z5ebmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shrimp" /></template>
