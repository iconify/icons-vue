<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4maro1xq.css';
import '../../css/y/y8xv1v9hl.css';
import '../../css/t/t4wa6sbad.css';
import '../../css/z/zkc3a6ybf.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4maro1xq"/><path class="y8xv1v9hl"/><path class="t4wa6sbad"/><path class="zkc3a6ybf"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tripod-foundation-20" /></template>
