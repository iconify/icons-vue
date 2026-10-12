<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-ihs8boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-ihs8boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medical-cross-20-bold" /></template>
