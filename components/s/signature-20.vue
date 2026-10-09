<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrvyqicgf.css';
import '../../css/h/hxwgvtb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hrvyqicgf"/><path class="hxwgvtb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signature-20" /></template>
