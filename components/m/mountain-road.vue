<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsuh-fbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vsuh-fbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mountain-road" /></template>
