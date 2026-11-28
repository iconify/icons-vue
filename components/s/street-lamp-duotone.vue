<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo2ys05zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo2ys05zc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:street-lamp-duotone" /></template>
