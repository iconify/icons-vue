<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6l5shx1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6l5shx1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pauldrons" /></template>
