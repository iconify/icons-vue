<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htq3a-brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htq3a-brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quarto" /></template>
