<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doj8pis9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="doj8pis9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:upwards-button" /></template>
