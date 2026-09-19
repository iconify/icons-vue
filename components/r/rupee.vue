<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rogyzp3fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":928,"height":1408};
const content = `<path class="rogyzp3fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rupee" /></template>
