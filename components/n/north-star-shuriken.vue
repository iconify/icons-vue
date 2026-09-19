<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4z9n5bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4z9n5bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:north-star-shuriken" /></template>
