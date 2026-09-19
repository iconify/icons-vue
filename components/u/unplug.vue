<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq2m4g_iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eq2m4g_iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unplug" /></template>
