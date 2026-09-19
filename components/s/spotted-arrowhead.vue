<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns4zjml5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ns4zjml5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spotted-arrowhead" /></template>
