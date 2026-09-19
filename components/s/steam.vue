<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfcjkqdzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfcjkqdzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:steam" /></template>
