<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sszangbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sszangbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sunflower" /></template>
