<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7sox82ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7sox82ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rocket-flight" /></template>
