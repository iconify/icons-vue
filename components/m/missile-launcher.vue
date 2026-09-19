<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w94jr_bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w94jr_bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:missile-launcher" /></template>
