<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5xt8ebyb.css';
import '../../css/y/yls_sbcyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5xt8ebyb"/><path class="yls_sbcyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:req" /></template>
