<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojxxti0kr.css';
import '../../css/m/mtxypiqix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojxxti0kr"/><path class="mtxypiqix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waypoints-20-bold" /></template>
