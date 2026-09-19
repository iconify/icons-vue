<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvsqusbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="cvsqusbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:right-circle" /></template>
