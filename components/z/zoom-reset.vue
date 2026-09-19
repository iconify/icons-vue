<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hom3-lb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hom3-lb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-reset" /></template>
