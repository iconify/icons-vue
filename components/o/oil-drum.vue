<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whnd-fbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whnd-fbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oil-drum" /></template>
