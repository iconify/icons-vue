<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs5vxub9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gs5vxub9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pathfinder-union-solid" /></template>
