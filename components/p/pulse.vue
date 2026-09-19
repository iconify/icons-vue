<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3yw4b3zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3yw4b3zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pulse" /></template>
