<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s89r-jghf.css';
import '../../css/z/ztpyv-0ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s89r-jghf"/><path class="ztpyv-0ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nodule-20" /></template>
