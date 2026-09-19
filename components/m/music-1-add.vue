<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usc5tqbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usc5tqbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:music-1-add" /></template>
