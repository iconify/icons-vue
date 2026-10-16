<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz1stbdx.css';
import '../../css/z/zcjjpsg5p.css';
import '../../css/t/te4svyq0w.css';
import '../../css/v/vftp51bjb.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="piz1stbdx"/><path class="zcjjpsg5p"/><path class="te4svyq0w"/><path class="vftp51bjb"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-x-20-bold" /></template>
