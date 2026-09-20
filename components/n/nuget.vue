<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he90tkigr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="he90tkigr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuget" /></template>
