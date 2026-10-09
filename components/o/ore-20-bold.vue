<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmpt51hmn.css';
import '../../css/z/zfhxusean.css';
import '../../css/y/y-rk38d9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jmpt51hmn"/><path class="zfhxusean"/><path class="y-rk38d9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ore-20-bold" /></template>
