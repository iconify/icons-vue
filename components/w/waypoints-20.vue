<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv9_vcbch.css';
import '../../css/g/glyz50bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pv9_vcbch"/><path class="glyz50bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waypoints-20" /></template>
