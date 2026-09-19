<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asdlnrbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":820};
const content = `<path class="asdlnrbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:pencil" /></template>
