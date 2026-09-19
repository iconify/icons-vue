<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ope7bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_ope7bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:traffic-lights-orange" /></template>
