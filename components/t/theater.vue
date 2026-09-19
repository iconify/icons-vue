<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyyaptw9m.css';
import '../../css/g/g2y0sfb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hyyaptw9m"/><path class="g2y0sfb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:theater" /></template>
