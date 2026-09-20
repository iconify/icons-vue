<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9sjl02ro.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/m/m3bbyvbqu.css';
import '../../css/p/ppf1pcc6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="r9sjl02ro"/><g class="kdz4acc8r"><path class="m3bbyvbqu"/><path class="ppf1pcc6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:speaking-head" /></template>
