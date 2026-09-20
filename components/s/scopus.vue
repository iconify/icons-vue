<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzv-z1sfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzv-z1sfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scopus" /></template>
