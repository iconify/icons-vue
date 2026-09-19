<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrw6p6brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jrw6p6brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:migrate-alt" /></template>
