<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucl-n6z2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucl-n6z2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-undo" /></template>
