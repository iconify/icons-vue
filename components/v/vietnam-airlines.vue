<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-6p3jmhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1515,"height":912};
const content = `<path class="i-6p3jmhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vietnam-airlines" /></template>
