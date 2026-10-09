<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp_m7046n.css';
import '../../css/y/y2nhzjrjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tp_m7046n"/><path class="y2nhzjrjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-20" /></template>
