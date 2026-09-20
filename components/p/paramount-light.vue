<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6yo2cn0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":118,"height":27};
const content = `<path class="m6yo2cn0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paramount-light" /></template>
