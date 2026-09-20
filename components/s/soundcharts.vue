<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrs30zsbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrs30zsbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:soundcharts" /></template>
