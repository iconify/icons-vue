<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2hkb1fev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2hkb1fev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:playlist-x" /></template>
