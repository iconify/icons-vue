<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixr70_7ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixr70_7ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vending-machine" /></template>
