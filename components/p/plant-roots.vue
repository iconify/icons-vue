<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-oh503pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-oh503pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plant-roots" /></template>
