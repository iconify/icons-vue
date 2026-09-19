<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9nk1jhad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f9nk1jhad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-stroke-12" /></template>
