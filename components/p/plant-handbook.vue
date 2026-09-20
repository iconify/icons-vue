<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpn46ob-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wpn46ob-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-handbook" /></template>
