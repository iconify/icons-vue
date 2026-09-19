<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5e10sboi.css';
import '../../css/n/n_757dk6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5e10sboi"/><path class="n_757dk6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reminder" /></template>
