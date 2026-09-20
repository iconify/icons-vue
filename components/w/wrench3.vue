<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-h28mb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x-h28mb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:wrench3" /></template>
