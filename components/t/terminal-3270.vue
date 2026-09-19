<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu63veedq.css';
import '../../css/q/qu9ohiqrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nu63veedq"/><path class="qu9ohiqrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:terminal-3270" /></template>
