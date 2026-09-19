<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2rti4btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="h2rti4btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:restroom" /></template>
