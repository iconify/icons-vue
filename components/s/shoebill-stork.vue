<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4s-6bdcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4s-6bdcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shoebill-stork" /></template>
