<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooyh4zckz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ooyh4zckz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:palmr-dark" /></template>
