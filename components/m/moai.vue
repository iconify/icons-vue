<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-5itzcvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-5itzcvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:moai" /></template>
