<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhx872bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhx872bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plus" /></template>
