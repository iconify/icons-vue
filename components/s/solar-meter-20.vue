<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3ux1061w.css';
import '../../css/h/hupodmbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ux1061w"/><path class="hupodmbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-meter-20" /></template>
