<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruh8bqbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ruh8bqbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-under-gabled-roof" /></template>
