<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viie0hb-o.css';
import '../../css/f/fiyd37bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="viie0hb-o"/><path class="fiyd37bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:power" /></template>
