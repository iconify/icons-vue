<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3_0h0bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h3_0h0bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:terminal" /></template>
