<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-h4bc3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z7-h4bc3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:veri" /></template>
