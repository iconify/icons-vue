<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9vad2brh.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wkcukxw1e.css';
import '../../css/m/md286fbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVGBKaMBekK" class="c9vad2brh"/></defs><g class="ft5dv1b6b"><circle class="wkcukxw1e"/><g class="md286fbip"><use href="#SVGBKaMBekK"/><use href="#SVGBKaMBekK"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:ost" /></template>
