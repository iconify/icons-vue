<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq23lwb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq23lwb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shield-opposition" /></template>
