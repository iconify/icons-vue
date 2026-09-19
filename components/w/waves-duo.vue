<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr5ehxn3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nr5ehxn3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:waves-duo" /></template>
