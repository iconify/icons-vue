<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzdkt5_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czzdkt5_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfcraft-light" /></template>
