<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0uh53i7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m0uh53i7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-slash-thin" /></template>
