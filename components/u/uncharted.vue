<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4svqmplo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u4svqmplo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:uncharted" /></template>
