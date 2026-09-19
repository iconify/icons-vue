<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok4pix9fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ok4pix9fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:rails" /></template>
