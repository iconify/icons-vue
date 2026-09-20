<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jejrh1gth.css';
import '../../css/v/vym5f4c_s.css';
import '../../css/o/optgq2b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jejrh1gth"/><path class="vym5f4c_s"/><path class="optgq2b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pear" /></template>
