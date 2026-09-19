<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt50z_byh.css';
import '../../css/v/v1lzvlbpn.css';
import '../../css/h/h65up44bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gt50z_byh"/><path class="v1lzvlbpn"/><path class="h65up44bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rstudio" /></template>
