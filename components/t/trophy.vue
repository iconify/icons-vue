<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj6ll6ylr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hj6ll6ylr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:trophy" /></template>
