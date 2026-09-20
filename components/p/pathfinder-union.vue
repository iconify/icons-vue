<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyox18xaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gyox18xaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pathfinder-union" /></template>
