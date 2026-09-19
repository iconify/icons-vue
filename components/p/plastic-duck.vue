<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/panbmsbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="panbmsbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plastic-duck" /></template>
