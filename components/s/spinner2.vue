<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay1_04bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ay1_04bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:spinner2" /></template>
