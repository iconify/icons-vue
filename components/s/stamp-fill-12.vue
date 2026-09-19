<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4d8bzb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r4d8bzb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:stamp-fill-12" /></template>
