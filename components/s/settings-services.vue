<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_06tclpl.css';
import '../../css/z/z2y88ibfp.css';
import '../../css/g/govmrcrfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p_06tclpl"/><path class="z2y88ibfp"/><path class="govmrcrfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings-services" /></template>
