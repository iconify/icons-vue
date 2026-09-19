<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q05doo8qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q05doo8qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-path" /></template>
