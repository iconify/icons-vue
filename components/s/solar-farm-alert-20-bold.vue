<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz1stbdx.css';
import '../../css/z/zcjjpsg5p.css';
import '../../css/t/te4svyq0w.css';
import '../../css/v/vftp51bjb.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="piz1stbdx"/><path class="zcjjpsg5p"/><path class="te4svyq0w"/><path class="vftp51bjb"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-alert-20-bold" /></template>
