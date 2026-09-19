<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c03nerhta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c03nerhta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pencil-ruler" /></template>
