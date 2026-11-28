<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfhv29b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfhv29b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:snowman" /></template>
