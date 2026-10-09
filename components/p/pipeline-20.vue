<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-adm0bmn.css';
import '../../css/z/zdes4i07z.css';
import '../../css/o/oawqqplkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-adm0bmn"/><path class="zdes4i07z"/><path class="oawqqplkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-20" /></template>
