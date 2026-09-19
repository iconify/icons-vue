<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr7k__z1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr7k__z1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ringed-beam" /></template>
