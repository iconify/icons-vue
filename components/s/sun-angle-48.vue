<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_49f5bfn.css';
import '../../css/o/oz7q2qb4l.css';
import '../../css/q/qxq5b3bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_49f5bfn"/><path class="oz7q2qb4l"/><path class="qxq5b3bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-angle-48" /></template>
