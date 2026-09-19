<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud59pdg3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud59pdg3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:poppy" /></template>
