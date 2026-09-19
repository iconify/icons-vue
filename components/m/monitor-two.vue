<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzpyehbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpyehbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:monitor-two" /></template>
