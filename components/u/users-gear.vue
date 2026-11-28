<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7sqflb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7sqflb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:users-gear" /></template>
