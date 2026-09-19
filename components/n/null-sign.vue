<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubmhn9bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubmhn9bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:null-sign" /></template>
