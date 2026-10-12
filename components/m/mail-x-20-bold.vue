<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvpdrtm6x.css';
import '../../css/k/kgx7jsbsk.css';
import '../../css/x/xak2o0bmu.css';
import '../../css/k/k6sa60boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lvpdrtm6x"/><path class="kgx7jsbsk"/><path class="xak2o0bmu"/><path class="k6sa60boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-x-20-bold" /></template>
