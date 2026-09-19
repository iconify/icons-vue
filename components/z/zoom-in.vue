<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im5r2tbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="im5r2tbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:zoom-in" /></template>
