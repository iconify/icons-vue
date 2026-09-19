<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laa_ont7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="laa_ont7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sliced-mushroom" /></template>
