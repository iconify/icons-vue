<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urnq0wzqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="urnq0wzqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:traefikproxy-wordmark" /></template>
