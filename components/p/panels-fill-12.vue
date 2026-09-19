<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7_i8lbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n7_i8lbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:panels-fill-12" /></template>
