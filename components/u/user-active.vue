<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohd3jjbmj.css';
import '../../css/h/hhno8jbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ohd3jjbmj"/><circle class="hhno8jbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-active" /></template>
