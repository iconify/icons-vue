<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cblm0_q7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cblm0_q7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:quora" /></template>
