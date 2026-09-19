<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot4szdbar.css';
import '../../css/n/niefumugv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ot4szdbar"/><path class="niefumugv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-analytics" /></template>
