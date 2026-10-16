<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ily569bri.css';
import '../../css/w/wegqv6blc.css';
import '../../css/e/ed4mxccbx.css';
import '../../css/e/eqdr87b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ily569bri"/><path class="wegqv6blc"/><path class="ed4mxccbx"/><path class="eqdr87b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-x-20" /></template>
