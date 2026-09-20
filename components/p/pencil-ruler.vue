<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-ce4rbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ce4rbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-ruler" /></template>
