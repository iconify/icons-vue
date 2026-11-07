<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f3oj9ibrq.css';
import '../../css/h/hmsxxdbnu.css';
import '../../css/i/icj9c585j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f3oj9ibrq"/><path class="hmsxxdbnu"/><path class="icj9c585j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-line-duotone" /></template>
