<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amlj5scla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amlj5scla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nessus" /></template>
