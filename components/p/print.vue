<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0w3icfad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g0w3icfad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:print" /></template>
