<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukg4327zf.css';
import '../../css/h/hc8c97wzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukg4327zf"/><path class="hc8c97wzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-20-bold" /></template>
