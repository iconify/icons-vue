<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u--1m-bou.css';
import '../../css/v/vidg63bsd.css';
import '../../css/p/pocrugbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u--1m-bou"/><path class="vidg63bsd"/><path class="pocrugbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:three-squares-bold" /></template>
