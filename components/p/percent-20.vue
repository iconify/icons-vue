<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0vjpuw4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0vjpuw4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:percent-20" /></template>
