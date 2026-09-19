<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb37wj2kt.css';
import '../../css/k/k8xftibiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cb37wj2kt"/><path class="k8xftibiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:statistic-map" /></template>
