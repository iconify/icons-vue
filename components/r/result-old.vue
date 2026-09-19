<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkynldbkl.css';
import '../../css/y/y_r_lzbqt.css';
import '../../css/h/hislmmgbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pkynldbkl"/><path class="y_r_lzbqt"/><path class="hislmmgbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:result-old" /></template>
