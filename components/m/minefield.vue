<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkdvj_bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkdvj_bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:minefield" /></template>
