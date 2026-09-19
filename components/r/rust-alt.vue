<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys6lkqbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ys6lkqbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rust-alt" /></template>
