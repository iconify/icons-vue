<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txbgyac2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txbgyac2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paw-front" /></template>
