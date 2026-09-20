<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9cynrzbj.css';
import '../../css/z/zqfr18vyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9cynrzbj"/><path class="zqfr18vyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typescript" /></template>
