<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzzsj1bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzzsj1bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:prism" /></template>
