<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytjf0pb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytjf0pb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tied-scroll" /></template>
