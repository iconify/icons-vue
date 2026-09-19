<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gijfkbcsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1600};
const content = `<path class="gijfkbcsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:upload" /></template>
