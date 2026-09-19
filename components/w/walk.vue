<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7zv2cbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":464};
const content = `<path class="h7zv2cbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:walk" /></template>
