<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0uubpijb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y0uubpijb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:rocket" /></template>
