<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl3uy_3rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kl3uy_3rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:shotgrid-wordmark" /></template>
