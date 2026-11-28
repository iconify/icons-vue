<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtg_mtnil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtg_mtnil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square" /></template>
