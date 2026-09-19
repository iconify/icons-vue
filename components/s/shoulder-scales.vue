<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbl3c2qzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbl3c2qzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shoulder-scales" /></template>
