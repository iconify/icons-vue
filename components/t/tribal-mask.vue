<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcx4orqhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcx4orqhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tribal-mask" /></template>
