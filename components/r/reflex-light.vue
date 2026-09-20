<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sldau_bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":12};
const content = `<path class="sldau_bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reflex-light" /></template>
