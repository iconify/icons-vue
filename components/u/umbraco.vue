<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2h2m0ymo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a2h2m0ymo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:umbraco" /></template>
