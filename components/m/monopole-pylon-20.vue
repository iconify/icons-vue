<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojf58obzl.css';
import '../../css/z/zi9baroae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojf58obzl"/><path class="zi9baroae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopole-pylon-20" /></template>
