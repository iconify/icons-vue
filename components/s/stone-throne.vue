<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8gv7b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-8gv7b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-throne" /></template>
