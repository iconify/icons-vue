<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw96zobvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nw96zobvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:satellite" /></template>
