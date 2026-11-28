<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_9rpuy_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_9rpuy_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:router-gear" /></template>
