<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl9i5p93o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":69.5,"height":59};
const content = `<path class="xl9i5p93o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ramp" /></template>
