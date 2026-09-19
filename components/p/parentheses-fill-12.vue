<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ico7ur4iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ico7ur4iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:parentheses-fill-12" /></template>
