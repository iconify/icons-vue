<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucme140zl.css';
import '../../css/m/mi8bjn4ds.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ucme140zl"/><path class="mi8bjn4ds"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tension-leg-20-bold" /></template>
