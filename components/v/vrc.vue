<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg2o5wied.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rg2o5wied"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:vrc" /></template>
