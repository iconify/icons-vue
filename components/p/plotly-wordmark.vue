<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cif8afbhr.css';
import '../../css/y/y9fgjabwe.css';
import '../../css/z/zer1teyxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cif8afbhr"/><path class="y9fgjabwe"/><path class="zer1teyxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:plotly-wordmark" /></template>
