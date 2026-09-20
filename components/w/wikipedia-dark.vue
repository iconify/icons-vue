<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on5wcqudm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="on5wcqudm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wikipedia-dark" /></template>
