<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv4lesbfb.css';
import '../../css/g/grzy5p8dw.css';
import '../../css/z/zz1xf7bjf.css';
import '../../css/t/tnr26c-cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vv4lesbfb"/><path class="grzy5p8dw"/><path class="zz1xf7bjf"/><path class="tnr26c-cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motorcycle-20" /></template>
