<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc_dg99_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc_dg99_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tv" /></template>
