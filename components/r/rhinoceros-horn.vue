<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vcnf70z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5vcnf70z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rhinoceros-horn" /></template>
