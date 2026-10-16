<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz1stbdx.css';
import '../../css/z/zcjjpsg5p.css';
import '../../css/t/te4svyq0w.css';
import '../../css/v/vftp51bjb.css';
import '../../css/a/asc4-fm2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="piz1stbdx"/><path class="zcjjpsg5p"/><path class="te4svyq0w"/><path class="vftp51bjb"/><path class="asc4-fm2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-check-20-bold" /></template>
