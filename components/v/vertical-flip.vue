<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp210-bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dp210-bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vertical-flip" /></template>
