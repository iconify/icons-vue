<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln82p3b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ln82p3b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thompson-m1" /></template>
