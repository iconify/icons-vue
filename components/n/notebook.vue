<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-84n2b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-84n2b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:notebook" /></template>
