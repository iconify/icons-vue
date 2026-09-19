<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcamlfw4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcamlfw4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soul-vessel" /></template>
