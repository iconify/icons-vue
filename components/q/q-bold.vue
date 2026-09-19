<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukf4kubog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ukf4kubog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:q-bold" /></template>
