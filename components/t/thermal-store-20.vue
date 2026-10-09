<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha3x0fenn.css';
import '../../css/g/ge-9v90ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ha3x0fenn"/><path class="ge-9v90ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-store-20" /></template>
