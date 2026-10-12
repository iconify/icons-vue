<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_54f839h.css';
import '../../css/n/nrm4cfbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_54f839h"/><path class="nrm4cfbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paragraph-20" /></template>
