<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgjulrbun.css';
import '../../css/w/w558l_3fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgjulrbun"/><path class="w558l_3fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-flash-off" /></template>
