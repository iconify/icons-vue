<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0p0d2yta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0p0d2yta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:toaster" /></template>
