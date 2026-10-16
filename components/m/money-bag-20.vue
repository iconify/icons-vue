<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz03-sdij.css';
import '../../css/a/ajbkkgb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lz03-sdij"/><path class="ajbkkgb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:money-bag-20" /></template>
