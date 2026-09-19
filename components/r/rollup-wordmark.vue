<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq-55_boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sq-55_boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rollup-wordmark" /></template>
