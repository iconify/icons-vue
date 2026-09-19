<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3nfk9boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="h3nfk9boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:reacteurope" /></template>
