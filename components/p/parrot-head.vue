<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or70bzl6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or70bzl6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:parrot-head" /></template>
