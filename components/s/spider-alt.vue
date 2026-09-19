<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5wgs_bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5wgs_bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spider-alt" /></template>
