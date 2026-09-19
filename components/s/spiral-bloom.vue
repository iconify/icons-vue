<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdn_s7btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdn_s7btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiral-bloom" /></template>
