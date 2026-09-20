<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tocp86bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tocp86bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:map-alt-1" /></template>
