<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbawec0hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lbawec0hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:primitive-necklace" /></template>
