<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okaev_bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okaev_bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-axe" /></template>
