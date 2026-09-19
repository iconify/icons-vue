<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua8c-eb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ua8c-eb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:pen" /></template>
