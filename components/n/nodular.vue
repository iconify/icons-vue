<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2h2jo7ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2h2jo7ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nodular" /></template>
