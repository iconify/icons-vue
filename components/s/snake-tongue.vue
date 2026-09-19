<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-1y49bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-1y49bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snake-tongue" /></template>
