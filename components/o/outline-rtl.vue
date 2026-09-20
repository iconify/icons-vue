<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofc0q49tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofc0q49tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:outline-rtl" /></template>
