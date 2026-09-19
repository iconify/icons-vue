<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcc7plb6l.css';
import '../../css/r/rhcdyqe0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hcc7plb6l"/><path class="rhcdyqe0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-nutrition" /></template>
