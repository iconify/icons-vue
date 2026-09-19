<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-y3ywbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-y3ywbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunbeams" /></template>
