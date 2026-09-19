<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke6ghzira.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="ke6ghzira"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:noborders" /></template>
