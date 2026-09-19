<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/iusjtvbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 5.75 1.75 14.25 1.75 14.25 14.25 14.25 14.25 5.75 10.75 1.75 5.25 1.75"/><path class="iusjtvbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:package" /></template>
