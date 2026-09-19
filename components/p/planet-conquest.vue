<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpohhcnht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kpohhcnht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:planet-conquest" /></template>
