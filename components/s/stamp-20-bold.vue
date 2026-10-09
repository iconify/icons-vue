<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he4rpzjtd.css';
import '../../css/c/cv0y15bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="he4rpzjtd"/><path class="cv0y15bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stamp-20-bold" /></template>
