<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgbheebyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1792};
const content = `<path class="dgbheebyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mars-stroke-v" /></template>
