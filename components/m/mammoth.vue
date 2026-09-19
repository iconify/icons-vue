<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odhxa5e7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odhxa5e7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mammoth" /></template>
