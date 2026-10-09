<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utpm0pbkq.css';
import '../../css/g/gl28njbdi.css';
import '../../css/m/m-7py9b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utpm0pbkq"/><path class="gl28njbdi"/><path class="m-7py9b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mirror-20" /></template>
