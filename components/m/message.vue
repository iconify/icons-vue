<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwz5z9bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwz5z9bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message" /></template>
