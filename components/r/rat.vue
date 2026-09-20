<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaax8ab6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gaax8ab6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rat" /></template>
