<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj6a1we8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lj6a1we8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plants-and-animals" /></template>
