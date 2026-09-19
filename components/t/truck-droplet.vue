<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isoiw1bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="isoiw1bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:truck-droplet" /></template>
