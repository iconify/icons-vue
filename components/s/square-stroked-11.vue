<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etpkxhbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="etpkxhbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:square-stroked-11" /></template>
