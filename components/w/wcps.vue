<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_mtoccrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f_mtoccrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wcps" /></template>
