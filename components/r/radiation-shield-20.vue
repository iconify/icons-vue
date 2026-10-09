<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkihj-w6g.css';
import '../../css/f/fe8opcc3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="fe8opcc3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-shield-20" /></template>
