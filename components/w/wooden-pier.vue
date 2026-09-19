<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2det2rzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2det2rzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wooden-pier" /></template>
