<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gk3cces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u7gk3cces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:zend-wordmark" /></template>
