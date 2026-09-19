<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd9kb2bas.css';
import '../../css/l/l19uj4vqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dd9kb2bas"/><path class="l19uj4vqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:netlify-wordmark" /></template>
