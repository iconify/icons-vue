<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2pw6cbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2pw6cbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:paint-bucket" /></template>
