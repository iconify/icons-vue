<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m19cgrbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m19cgrbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pydantic" /></template>
