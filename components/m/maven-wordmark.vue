<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou83dy36f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ou83dy36f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:maven-wordmark" /></template>
