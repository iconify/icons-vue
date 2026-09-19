<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6uzq7bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n6uzq7bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:share" /></template>
