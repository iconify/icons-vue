<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzy7q7fnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rzy7q7fnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:viadeo" /></template>
