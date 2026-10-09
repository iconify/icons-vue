<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bohi61rzr.css';
import '../../css/v/v1gt_db3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bohi61rzr"/><path class="v1gt_db3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torch-20-bold" /></template>
