<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztm991_5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztm991_5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wine-bottle" /></template>
