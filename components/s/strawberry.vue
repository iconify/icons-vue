<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uorm58bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uorm58bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:strawberry" /></template>
