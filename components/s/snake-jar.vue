<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp26bdkej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp26bdkej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snake-jar" /></template>
