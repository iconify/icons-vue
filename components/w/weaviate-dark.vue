<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2rhl-nvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2rhl-nvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weaviate-dark" /></template>
