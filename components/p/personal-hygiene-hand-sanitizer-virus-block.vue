<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/irmit6ben.css';
import '../../css/c/cf-ba1bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="irmit6ben"/><path class="cf-ba1bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-hand-sanitizer-virus-block" /></template>
